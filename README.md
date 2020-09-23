# patterns-in-python
how you can create patterns in python



# 1) square patterns (a)


for i in range (4) :   
    for i in range(4):
        print("# ", end = " ")
    print()
    
##output##   
    
                #  #  #  #
                #  #  #  #
                #  #  #  #
                #  #  #  #
    
    
    

# square(b)

num = int(input("enter num: "))
for i in range (num) :   
    print("# "*num)
    
 ##output##
 enter num: 5
 
 
                # # # # #
                # # # # #
                # # # # #
                # # # # #
                # # # # #



# 2)triangle pattern (a1)
num = int(input("enter num: "))
for i in range (num) :   
    for i in range(i+1):
        print("# ", end = " ")
    print()
    
    or
    
    
 # triangle pattern (a2)
num = int(input("enter num: "))
for i in range (1,num+1) :   
    print("# "*i)

 ##output##
  enter num: 5
  
  
                        #
                        #  #
                        #  #  #
                        #  #  #  #
                        #  #  #  #  #




# triangle pattern (b1)
num = int(input("enter num: "))
for i in range (num,0,-1) :   
    for i in range(i):
        print("# ", end = " ")
    print()
    
    or
    
# triangle pattern (b2)   
num = int(input("enter num: "))
for i in range (num,0,-1) :   
    print("# "*i)
    
 ##output##   
  enter num: 5
                                #  #  #  #  #
                                #  #  #  #
                                #  #  #
                                #  #
                                #

# triangle (a) + (b)
num = int(input("enter num: "))
for i in range (num) :   
    for i in range(i+1):
        print("# ", end = " ")
    print()

for i in range (num,0,-1) :   
    for i in range(i-1):   
        print("# ", end = " ")
    print()
    
    ##output##
     enter num: 6
                                    #
                                    #  #
                                    #  #  #
                                    #  #  #  #
                                    #  #  #  #  #
                                    #  #  #  #  #  #
                                    #  #  #  #  #
                                    #  #  #  #
                                    #  #  #
                                    #  #
                                    #



# triangle(c)

num = int(input("enter num: "))
for i in range (1,num+1) :   
    print("  "*(num-i)+ "# "*i)
    
    ##output##
  enter num: 4
                                  #
                                # #
                              # # #
                            # # # #


# triangle(d)


num = int(input("enter num: "))
for i in range (1,num+1) :   
    print(" "*(num-i)+ "# "*i)
    
    ##output##
    enter num: 6
                                 #
                                # #
                               # # #
                              # # # #
                             # # # # #
                            # # # # # #



# triangle (e) diamond shape

num = int(input("enter num: "))
for i in range (1,num+1) :   
    print(" "*(num-i)+ "# "*i)
    
for i in range (num-1,0,-1) :   
    print(" "*(num-i)+ "# "*i)
    
    ##output##
   enter num: 5
                                        #
                                       # #
                                      # # #
                                     # # # #
                                    # # # # #
                                     # # # #
                                      # # #
                                       # #
                                        #


