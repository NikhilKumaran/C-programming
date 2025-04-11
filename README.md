
# C programming

# Introduction
#1) Keywords-32
#2) Operators-45 (+,-,*,/,%,<,>,etc..)

    1)Arithmetic Operator:
        (+,-,*,/,%,++,--,..)

        ++ -Increment (+1)
        -- -Decrement (-)

        ++a (preincrement)  a++(postincrement)

    2)Relational Operator:

        ( <= , >= , == , != ,< , > )

    3)Logical Operator:

        ( && , || , ! )

        && - both condition should be true
        || - either one should be true
        ! -  It will flip the value (0 to 1) and (1 to 0)

    4)Assignment Operator:

            ( = , += , -= , *= , /= , %= )
            
            int a=10;
            a+=10;

    
    5)Unary Operator:

        ( ! , ++ , --)

    6)Binary Operator:

        ( && , || , < , > )

    7)ConditionL Operator:

        ( ? , : )

        syntax: arg1?arg2:arg3

        eg:
            (3>2)? printf("3 is greater") : printf("@ is greater");




#3) Separators-14 (;,{},[],#,,,etc..)

    (,) -separates multiple variable

    ; -Ends a statement

    {} -Defines the  block of code

    ()-Used in function calls,conditions loops

    []-Array declaration

    '#' -preprocessor

#4)Format Specifier 

    (%d,%s,%f,%c)

    d-Integer

    s-string

    f-float

    c-char

    ld-long int

    short int-hd

    eg:

        int a;

        printf("Enter number A:");

        scanf("%d",&a);


#5)Comment:

    //-For single line Comment

    /* */ -For multi line Comment

#6)DataType:

    A to Z

    a to z

  eg:

    int name=0

#7)To print:

    printf("Hello World ");

#8)ASCII Values:

    a to z= 97 to 122

    A to Z= 65 to 90

#9)To get input from user:

        scanf("%d",&a);

        eg:

            float side;

            printf("Enter length of side: ");

            scanf("%f",&side);



#10)getchar():

            to read one character at a time from the key board
            

#11)Priority:

        !

        / , * , %

        + , -

        < , > , <= , >=

        == , !=

        && , ||

        ? :
        
        =


#12)Loop:

        1)While

        2)For

        3)Do while

    1)While:
        syntax:
            declaration;
            while (condition) {
                statement
                steps    ( -- , ++)
            }


        eg:
            int a=0;
            while (a<=5){
                printf("hello\n");
                a+=1;
            }


    2)For:
        syntax:
                for(declaration;condition;steps) {
                    statement;
                }
        
        eg:
                for(int index=0;index<=5;index=++) {
                    printf("hello\n");
                }


    3)Do while:
        syntax:
            do{
                statement;
            }while(condition);


        eg:
            do{
                printf("Hello\n");
            }while(0);
