#Target_name : Dependencies
#<TAB>command
PROJECT_NAME = Marks.out
SRC = main.c

ifdef OS
    RM = del /q
    Fixpath = $(subst /,\,$1)
    EXEC = exe
else
    ifeq ($(shell uname) , Linux)
       RM = rm -rf
       Fixpath = $1
       EXEC = out
    endif
endif


$(PROJECT_NAME) : $(SRC)
    gcc $(SRC) -o $(call Fixpath,$(PROJECT_NAME).$(EXEC))

run : $(PROJECT_NAME)
    ./$(call Fixpath,$(PROJECT_NAME).$(EXEC))

clean:
    rm -rf *.out
