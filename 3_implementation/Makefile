#Target_name : Dependencies
#<TAB>command
MARKS = Feauture.out
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


$(MARKS) : $(main.c)
    gcc $(main.c) -o $(call Fixpath,$(MARKS).$(EXEC)

run : $(main.c)
    ./$(call Fixpath,$(Marks).$(EXEC))

clean:
    rm -rf *.out
