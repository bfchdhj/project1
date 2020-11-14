



      board = {'7': ' ' , '8': ' ' , '9': ' ' ,
            '4': ' ' , '5': ' ' , '6': ' ' ,
            '1': ' ' , '2': ' ' , '3': ' ' }
            def printboard(board);
            print(board['7'] + '|' + board['8'] + '|' + board['9'])
    print('-+-+-')
    print(board['4'] + '|' + board['5'] + '|' + board['6'])
    print('-+-+-')
    print(board['1'] + '|' + board['2'] + '|' + board['3'])
    
    def game():
    turn='X"
    count=0
    
    for i in range(10)
    printboard(board)
    print("your turn"+turn+"choose ur place")
    move=input();
    if board[move]==' ':
    board[move]=turn 
    count+=1
    else:
    print("Already filled")
    continue;
    
    if count>=5
            if theBoard['7'] == theBoard['8'] == theBoard['9'] != ' ':
    printboard(board)
    print("gameover")
    print(turn+"won')
    break
                            elif Board['4'] == theBoard['5'] == theBoard['6'] != ' ': # across the middle
                printBoard(theBoard)
                print("\nGame Over.\n")                
                print(" **** " +turn + " won. ****")
                break
                     elif theBoard['1'] == theBoard['2'] == theBoard['3'] != ' ': # across the bottom
                printBoard(theBoard)
                print("\nGame Over.\n")                
                print(" **** " +turn + " won. ****")
                break
         elif theBoard['1'] == theBoard['4'] == theBoard['7'] != ' ': # down the left side
                printBoard(theBoard)
                print("\nGame Over.\n")                
                print(" **** " +turn + " won. ****")
                break
            
            
            
               elif theBoard['2'] == theBoard['5'] == theBoard['8'] != ' ': # down the middle
                printBoard(theBoard)
                print("\nGame Over.\n")                
                print(" **** " +turn + " won. ****")
                break
                      elif theBoard['3'] == theBoard['6'] == theBoard['9'] != ' ': # down the right side
                     printBoard(theBoard)
                print("\nGame Over.\n")                
                print(" **** " +turn + " won. ****")
                break 
        elif theBoard['7'] == theBoard['5'] == theBoard['3'] != ' ': # diagonal
                printBoard(theBoard)
                print("\nGame Over.\n")                
                print(" **** " +turn + " won. ****")
                break
                              elif theBoard['1'] == theBoard['5'] == theBoard['9'] != ' ': # diagonal
                printBoard(theBoard)
                print("\nGame Over.\n")                
                print(" **** " +turn + " won. ****")
                break
              
             if count==9:
                print("gameover")
               print("its a tie")
            
            
          if turn='X':
             turn='O'
            else 
             turn='X'
             
             restart=input("Do u wanna play again")
             
             
              
               
                
    
      
            














