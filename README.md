# Baseball-Sim
#Baseball simualtion

def boxScore():
  import random
  score1=0 #initializing team scores
  score2=0
  inning=0 #initializing variable inning
  error111=0 #initializing teams errors
  error222=0
  hits11=0.0
  hits1=0
  hits22=0.0
  hits2=0
  walkorhbp1=0
  walkorhbp2=0
  atbats1=0
  atbats2=0
  atBat1=0
  atBat2=0
  player11hits=0.0
  player11ab=0
  player11walkhbp=0
  player11rbi=0
  player12hits=0.0
  player12ab=0
  player12walkhbp=0
  player12rbi=0
  player13hits=0.0
  player13ab=0
  player13walkhbp=0
  player13rbi=0
  player14hits=0.0
  player14ab=0
  player14walkhbp=0
  player14rbi=0
  player15hits=0.0
  player15ab=0
  player15walkhbp=0
  player15rbi=0
  player16hits=0.0
  player16ab=0
  player16walkhbp=0
  player16rbi=0
  player17hits=0.0
  player17ab=0
  player17walkhbp=0
  player17rbi=0
  player18hits=0.0
  player18ab=0
  player18walkhbp=0
  player18rbi=0
  player19hits=0.0
  player19ab=0
  player19walkhbp=0
  player19rbi=0
  player21hits=0.0
  player21ab=0
  player21walkhbp=0
  player21rbi=0
  player22hits=0.0
  player22ab=0
  player22walkhbp=0
  player22rbi=0
  player23hits=0.0
  player23ab=0
  player23walkhbp=0
  player23rbi=0
  player24hits=0.0
  player24ab=0
  player24walkhbp=0
  player24rbi=0
  player25hits=0.0
  player25ab=0
  player25walkhbp=0
  player25rbi=0
  player26hits=0.0
  player26ab=0
  player26walkhbp=0
  player26rbi=0
  player27hits=0.0
  player27ab=0
  player27walkhbp=0
  player27rbi=0
  player28hits=0.0
  player28ab=0
  player28walkhbp=0
  player28rbi=0
  player29hits=0.0
  player29ab=0
  player29walkhbp=0
  player29rbi=0
  print"Build team one's Line-up."
  print"Whos is batting first?"
  player11=raw_input()
  print player11,"OBP:"
  obp1p1=input()
  print"AVG:"
  av1p1=input()
  print"Who is batting second?"
  player12=raw_input()
  print player12,"OBP:"
  obp1p2=input()
  print"AVG:"
  av1p2=input()
  print"Who is batting third?"
  player13=raw_input()
  print player13,"OBP:"
  obp1p3=input()
  print"AVG:"
  av1p3=input()
  print"Who is batting fourth?"
  player14=raw_input()
  print player14,"OBP:"
  obp1p4=input()
  print"AVG:"
  av1p4=input()
  print"Who is batting fifth?"
  player15=raw_input()
  print player15,"OBP:"
  obp1p5=input()
  print"AVG:"
  av1p5=input()
  print"Who is batting sixth?"
  player16=raw_input()
  print player16,"OBP:"
  obp1p6=input()
  print"AVG:"
  av1p6=input()
  print"Who is batting seventh?"
  player17=raw_input()
  print player17,"OBP:"
  obp1p7=input()
  print"AVG:"
  av1p7=input()
  print"Who is batting eight?"
  player18=raw_input()
  print player18,"OBP:"
  obp1p8=input()
  print"AVG:"
  av1p8=input()
  print"Who is batting ninth?"
  player19=raw_input()
  print"Player 9's OBP:"
  obp1p9=input()
  print"AVG:"
  av1p9=input()
  print"What is team 1's error percentage?"
  error1=input()
  print"Who is your starting pitcher?"
  pitcher11=raw_input()
  print pitcher11,"average against?"
  pitching1=input()
  print"Build team two's Line-up."
  print"Who is batting first?"
  player21=raw_input()
  print player21,"OBP:"
  obp2p1=input()
  print"AVG:"
  av2p1=input()
  print"Who is batting second?"
  player22=raw_input()
  print player22,"OBP:"
  obp2p2=input()
  print"AVG:"
  av2p2=input()
  print"Who is batting third"
  player23=raw_input()
  print player23,"OBP:"
  obp2p3=input()
  print"AVG:"
  av2p3=input()
  print"Who is batting fourth?"
  player24=raw_input()
  print player24,"OBP:"
  obp2p4=input()
  print"AVG:"
  av2p4=input()
  print"Who is batting fifth?"
  player25=raw_input()
  print player25,"OBP:"
  obp2p5=input()
  print"AVG:"
  av2p5=input()
  print"Who is batting sixth?"
  player26=raw_input()
  print player26,"OBP:"
  obp2p6=input()
  print"AVG:"
  av2p6=input()
  print "Who is batting seventh?"
  player27=raw_input()
  print player27,"OBP:"
  obp2p7=input()
  print"AVG:"
  av2p7=input()
  print"Who is batting eight?"
  player28=raw_input()
  print player28,"OBP:"
  obp2p8=input()
  print"AVG:"
  av2p8=input()
  print"Who is batting ninth?"
  player29=raw_input()
  print player29,"OBP:"
  obp2p9=input()
  print"AVG:"
  av2p9=input()
  print"What is team 2's error percentage?"
  error2=input()
  print"Who is the starting pitcher?"
  pitcher21=raw_input()
  print pitcher21,"average against?"
  pitching2=input()
  for inning in range(1,10): #for loop to span the entire game
    inningscore1=0 #keeps track of the runs scored in the particular inning
    hits3=0 #keeps track of hits in the inning
    menonbase1=0 #keeps track of the number of men team 1 has on base
    outs1=0 #starting the inning with 0 outs
    inningerror2=0 #counting the number of errors by team 2 in the inning
    inninghbp1=0 #counting the number of players hit by pitch in the inning
    while outs1<3:#loop counting the nuber of outs in team 1s half of the inning
      batterUp1=currentBatter1(atBat1)
      if batterUp1==0:
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p1)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          player11hits=player11hits+1
          player11ab=player11ab+1
          atBat1=1
          if menonbase1>3: #gives a run if bases are loaded
            score1=score1+1
            inningscore1=inningscore1+1
            player11rbi=player11rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p1)/2<pitch<obp1p1: #not a hit but not an out
          ballplay1=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay1<2: #ball is not in play, batter is walked or hit by pitch
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            player11walkhbp=player11walkhbp+1
            atbats1=atbats1
            atBat1=1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player11rbi=player11rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            player11ab=player11ab+1
            atbats1=atbats1+1
            atBat1=1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          player11ab=player11ab+1
          atbats1=atbats1+1
          atBat1=1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player11rbi=player11rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=1
          player11ab=player11ab+1
      elif batterUp1==1:
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p2)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=2
          player12hits=player12hits+1
          player12ab=player12ab+1
          if menonbase1>3: #gives a run if bases are loaded
            score1=score1+1
            inningscore1=inningscore1+1
            player12rbi=player12rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p2)/2<pitch<obp1p1: #not a hit but not an out
          ballplay1=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay1<2: #ball is not in play, batter is walked or hit by pitch
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            player12walkhpb=player12walkhbp+1
            atbats1=atbats1
            atBat1=2
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player12rbi=player12rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=2
            player12ab=player12ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=2
          player12ab=player12ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player12rbi=player12rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=2
          player12ab=player12ab+1
      elif batterUp1==2: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p3)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=3
          player13ab=player13ab+1
          player13hits=player13hits+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player13rbi=player13rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p3)/2<pitch<obp1p3:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            player13walkhbp=player13walkhbp+1
            atbats1=atbats1
            atBat1=3
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player13rbi=player13rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            player13ab=player13ab+1
            atBat1=3
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          player13ab=player13ab+1
          atBat1=3
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player13rbi=player13rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=3
          player13ab=player13ab+1
      elif batterUp1==3: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p4)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=4
          player14hits=player14hits+1
          player14ab=player14ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player14rbi=player14rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p4)/2<pitch<obp1p4:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            atBat1=4
            player14walkhbp=player14walkhbp+1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player14rbi=player14rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=4
            player14ab=player14ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          player14ab=player14ab+1
          atBat1=4
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player14rbi=player14rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=4
          player14ab=player14ab+1
      elif batterUp1==4: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p5)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=5
          player15hits=player15hits+1
          player15ab=player15ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player15rbi=player15rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p5)/2<pitch<obp1p5:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            player15walkhbp=player15walkhbp+1
            atbats1=atbats1
            atBat1=5
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player15rbi=player15rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=5
            player15ab=player15ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          player15ab=player15ab+1
          atBat1=5
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player15rbi=player15rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=5
          player15ab=player15ab+1
      elif batterUp1==5: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p6)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=6
          player16ab=player16ab+1
          player16hits=player16hits+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player16rbi=player16rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p6)/2<pitch<obp1p6:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            player16walkhbp=player16walkhbp+1
            atBat1=6
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player16rbi=player16rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            player16ab=player16ab+1
            atBat1=6
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=6
          player16ab=player16ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player16rbi=player16rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=6
          player16ab=player16ab+1
      elif batterUp1==6: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p7)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=7
          player17hits=player17hits+1
          player17ab=player17ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player17rbi=player17rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p7)/2<pitch<obp1p7:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            atBat1=7
            player17walkhbp=player17walkhbp+1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player17rbi=player17rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=7
            player17ab=player17ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=7
          player17ab=player17ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player17rbi=player17rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=7
          player17ab=player17ab+1
      elif batterUp1==7: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p8)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=8
          player18hits=player18hits+1
          player18ab=player18ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player18rbi=player18rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p8)/2<pitch<obp1p8:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            atBat1=8
            player18walkhbp=player18walkhbp+1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player18rbi=player18rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=8
            player18ab=player18ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=8
          player18ab=player18ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player18rbi=player18rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=8
          player18ab=player18ab+1
      else: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p9)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=9
          player19hits=player19hits+1
          player19ab=player19ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player19rbi=player19rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p9)/2<pitch<obp1p9:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            atBat1=9
            player19walkhbp=player19walkhbp+1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player19rbi=player19rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=9
            player19ab=player19ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=9
          player19ab=player19ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player19rbi=player19rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=9
          player19ab=player19ab+1
    if score2-score1>=5:
      print" Team 1 Bring in a new pitcher"
      print"Who is your reliever?"
      pitcher12=raw_input()
      print pitcher12,"average against?"
      pitching1=input()
    if inning==9:
      if score1-score2<=3 and score1-score2>0:
        print"Team 1 Bring in the closing pitcher"
        print"Who is your closer?"
        pitchercloser1=raw_input()
        print pitchercloser1,"average against?"
        pitching1=input()
    menonbase2=0
    inningscore2=0
    outs2=0
    inningerror1=0
    hits4=0
    inninghbp2=0 #!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!   
    while outs2<3:
      batterUp2=currentBatter2(atBat2)
      if batterUp2==0:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p1)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=1
          player21hits=player21hits+1
          player21ab=player21ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player21rbi=player21rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p1)/2<pitch2<obp2p1: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=1
            player21walkhbp=player21walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player21rbi=player21rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=1
            player21ab=player21ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=1
          player21ab=player21ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player21rbi=player21rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=1
          player21ab=player21ab+1
      elif batterUp2==1:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p2)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=2
          player22ab=player22ab+1
          player22hits=player22hits+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player22rbi=player22rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p2)/2<pitch2<obp2p2: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=2
            player22walkhbp=player22walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player22rbi=player22rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=2
            player22ab=player22ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          player22ab=player22ab+1
          atBat2=2
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player22rbi=player22rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=2
          player22ab=player22ab+1
      elif batterUp2==2:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p3)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=3
          player23hits=player23hits+1
          player23ab=player23ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player23rbi=player23rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p3)/2<pitch2<obp2p3: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=3
            player23walkhbp=player23walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player23rbi=player23rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=3
            player23ab=player23ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=3
          player23ab=player23ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player23rbi=player23rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=3
          player23ab=player23ab+1
      elif batterUp2==3:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p4)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=4
          player24hits=player24hits+1
          player24ab=player24ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player24rbi=player24rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p4)/2<pitch2<obp2p4: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=4
            player24walkhbp=player24walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player24rbi=player24rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=4
            player24ab=player24ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=4
          player24ab=player24ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player24rbi=player24rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=4
          player24ab=player24ab+1
      elif batterUp2==4:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p5)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=5
          player25hits=player25hits+1
          player25ab=player25ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player25rbi=player25rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p5)/2<pitch2<obp2p5: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=5
            player25walkhbp=player25walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player25rbi=player25rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=5
            player25ab=player25ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=5
          player25ab=player25ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player25rbi=player25rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=5
          player25ab=player25ab+1
      elif batterUp2==5:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p6)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=6
          player26hits=player26hits+1
          player26ab=player26ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player26rbi=player26rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p6)/2<pitch2<obp2p6: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=6
            player26walkhbp=player26walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player26rbi=player26rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=6
            player26ab=player26+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=6
          player26ab=player26ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player26rbi=player26rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=6
          player26ab=player26ab+1
      elif batterUp2==6:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p7)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=7
          player27ab=player27ab+1
          player27hits=player27hits+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player27rbi=player27rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p7)/2<pitch2<obp2p7: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=7
            player27walkhbp=player27walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player27rbi=player27rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=7
            player27ab=player27ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=7
          player27ab=player27ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player27rbi=player27rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=7
          player27ab=player27ab+1
      elif batterUp2==7:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p8)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=8
          player28hits=player28hits+1
          player28ab=player28ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player28rbi=player28rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p8)/2<pitch2<obp2p8: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=8
            player28walkhbp=player28walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player28rbi=player28rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=8
            player28ab=player28ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=8
          player28ab=player28ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player28rbi=player28rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=8
          player28ab=player28ab+1
      else:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p9)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=9
          player29hits=player29hits+1
          player29ab=player29ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player29rbi=player29rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p9)/2<pitch2<obp2p9: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=9
            player29walkhbp=player29walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player29rbi=player29rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=9
            player29ab=player29ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=9
          player29ab=player29ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player29rbi=player29rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=9
          player29ab=player29ab+1
    if score1-score2>=5:
      print"Team 2 Bring in a relief pitcher"
      print"Who is your relief pitcher?"
      pitcher22=raw_input()
      print pitcher22,"average against?"
      pitching2=input()
    if inning==9:
      if score2-score1<=3 and score2-score1>0:
        print"Team 2 Bring in your closer."
        print"Whos is your closer?"
        pitchercloser2=raw_input()
        print pitchercloser2,"average against?"
        pitching2=input()
    print"Inning:",inning
    print"Runs scored Red Sox:",inningscore1,"/Hits:",hits3,"/Walked or Hit by Pitch:",inninghbp1,"/Errors:",inningerror1
    print""
    print"Runs scored Yankees",inningscore2,"/Hits:",hits4,"/Walked or Hit by Pitch:",inninghbp2,"/Errors:",inningerror2
  inning=10
  while(score1==score2):
    inningscore1=0 #keeps track of the runs scored in the particular inning
    hits3=0 #keeps track of hits in the inning
    menonbase1=0 #keeps track of the number of men team 1 has on base
    outs1=0 #starting the inning with 0 outs
    inningerror2=0 #counting the number of errors by team 2 in the inning
    inninghbp1=0 #counting the number of players hit by pitch in the inning
    while outs1<3:#loop counting the nuber of outs in team 1s half of the inning
      batterUp1=currentBatter1(atBat1)
      if batterUp1==0:
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p1)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          player11hits=player11hits+1
          player11ab=player11ab+1
          atBat1=1
          if menonbase1>3: #gives a run if bases are loaded
            score1=score1+1
            inningscore1=inningscore1+1
            player11rbi=player11rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p1)/2<pitch<obp1p1: #not a hit but not an out
          ballplay1=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay1<2: #ball is not in play, batter is walked or hit by pitch
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            player11walkhbp=player11walkhbp+1
            atbats1=atbats1
            atBat1=1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player11rbi=player11rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            player11ab=player11ab+1
            atbats1=atbats1+1
            atBat1=1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          player11ab=player11ab+1
          atbats1=atbats1+1
          atBat1=1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player11rbi=playerrbi11+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=1
          player11ab=player11ab+1
      elif batterUp1==1:
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p2)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=2
          player12hits=player12hits+1
          player12ab=player12ab+1
          if menonbase1>3: #gives a run if bases are loaded
            score1=score1+1
            inningscore1=inningscore1+1
            player12rbi=player12rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p2)/2<pitch<obp1p1: #not a hit but not an out
          ballplay1=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay1<2: #ball is not in play, batter is walked or hit by pitch
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            player12walkhpb=player12walkhbp+1
            atbats1=atbats1
            atBat1=2
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player12rbi=player12rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=2
            player12ab=player12ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=2
          player12ab=player12ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player12rbi=player12rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=2
          player12ab=player12ab+1
      elif batterUp1==2: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p3)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=3
          player13ab=player13ab+1
          player13hits=player13hits+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player13rbi=player13rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p3)/2<pitch<obp1p3:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            player13walkhbp=player13walkhbp+1
            atbats1=atbats1
            atBat1=3
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player13rbi=player13rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            player13ab=player13ab+1
            atBat1=3
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          player13ab=player13ab+1
          atBat1=3
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player13rbi=player13rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=3
          player13ab=player13ab+1
      elif batterUp1==3: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p4)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=4
          player14hits=player14hits+1
          player14ab=player14ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player14rbi=player14rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p4)/2<pitch<obp1p4:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            atBat1=4
            player14walkhbp=player14walkhbp+1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player14rbi=player14rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=4
            player14ab=player14ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          player14ab=player14ab+1
          atBat1=4
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player14rbi=player14rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=4
          player14ab=player14ab+1
      elif batterUp1==4: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p5)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=5
          player15hits=player15hits+1
          player15ab=player15ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player15rbi=player15rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p5)/2<pitch<obp1p5:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            player15walkhbp=player15walkhbp+1
            atbats1=atbats1
            atBat1=5
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player15rbi=player15rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=5
            player15ab=player15ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          player15ab=player15ab+1
          atBat1=5
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player15rbi=player15rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=5
          player15ab=player15ab+1
      elif batterUp1==5: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p6)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=6
          player16ab=player16ab+1
          player16hits=player16hits+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player16rbi=player16rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p6)/2<pitch<obp1p6:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            player16walkhbp=player16walkhbp+1
            atBat1=6
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player16rbi=player16rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            player16ab=player16ab+1
            atBat1=6
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=6
          player16ab=player16ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player16rbi=player16rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=6
          player16ab=player16ab+1
      elif batterUp1==6: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p7)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=7
          player17hits=player17hits+1
          player17ab=player17ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player17rbi=player17rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p7)/2<pitch<obp1p7:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            atBat1=7
            player17walkhbp=player17walkhbp+1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player17rbi=player17rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=7
            player17ab=player17ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=7
          player17ab=player17ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player17rbi=player17rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=7
          player17ab=player17ab+1
      elif batterUp1==7: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p8)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=8
          player18hits=player18hits+1
          player18ab=player18ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player18rbi=player18rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p8)/2<pitch<obp1p8:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            atBat1=8
            player18walkhbp=player18walkhbp+1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player18rbi=player18rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=8
            player18ab=player18ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=8
          player18ab=player18ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player18rbi=player18rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=8
          player18ab=player18ab+1
      else: ########################################
        pitch=random.randint(1,1000) #getting a random integer to compare against other stats
        error12=random.randint(1,1000) #getting a number to compare against error stat
        if pitch<(pitching2+av1p9)/2: #this will give a base hit to player at bat
          menonbase1=menonbase1+1 #gives us a baserunner
          hits3=hits3+1 #gives us a hit in the inning
          hits1=hits1+1 #team 1 gets a hit in the game
          hits11=hits11+1 #team 1 gets a hit in the game
          atbats1=atbats1+1#at bat counter increases
          atBat1=9
          player19hits=player19hits+1
          player19ab=player19ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player19rbi=player19rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
        elif (pitching2+av1p9)/2<pitch<obp1p9:
          ballplay1=random.randint(1,2)
          if ballplay1<2:
            menonbase1=menonbase1+1
            walkorhbp1=walkorhbp1+1
            inninghbp1=inninghbp1+1
            atbats1=atbats1
            atBat1=9
            player19walkhbp=player19walkhbp+1
            if menonbase1>3:
              score1=score1+1
              inningscore1=inningscore1+1
              player19rbi=player19rbi+1
            else:
              score1=score1
              inningscore1=inningscore1
          else:
            outs1=outs1+1
            atbats1=atbats1+1
            atBat1=9
            player19ab=player19ab+1
        elif 1000-error12<error2:
          error222=error222+1
          menonbase1=menonbase1+1
          inningerror2=inningerror2+1
          atbats1=atbats1+1
          atBat1=9
          player19ab=player19ab+1
          if menonbase1>3:
            score1=score1+1
            inningscore1=inningscore1+1
            player19rbi=player19rbi+1
          else:
            score1=score1
            inningscore1=inningscore1
            inningerror2=inningerror2
        else:
          outs1=outs1+1
          atbats1=atbats1+1
          atBat1=9
          player19ab=player19ab+1
    if score2-score1>=5:
      print" Team 1 Bring in a new pitcher"
      print"Who is your reliever?"
      pitcher12=raw_input()
      print pitcher12,"average against?"
      pitching1=input()
    if inning==9:
      if score1-score2<=3 and score1-score2>0:
        print"Team 1 Bring in the closing pitcher"
        print"Who is your closer?"
        pitchercloser1=raw_input()
        print pitchercloser1,"average against?"
        pitching1=input()
    menonbase2=0
    inningscore2=0
    outs2=0
    inningerror1=0
    hits4=0
    inninghbp2=0 #!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!   
    while outs2<3:
      batterUp2=currentBatter2(atBat2)
      if batterUp2==0:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p1)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=1
          player21hits=player21hits+1
          player21ab=player21ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player21rbi=player21rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p1)/2<pitch2<obp2p1: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=1
            player21walkhbp=player21walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player21rbi=player21rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=1
            player21ab=player21ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=1
          player21ab=player21ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player21rbi=player21rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=1
          player21ab=player21ab+1
      elif batterUp2==1:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p2)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=2
          player22ab=player22ab+1
          player22hits=player22hits+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player22rbi=player22rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p2)/2<pitch2<obp2p2: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=2
            player22walkhbp=player22walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player22rbi=player22rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=2
            player22ab=player22ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          player22ab=player22ab+1
          atBat2=2
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player22rbi=player22rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=2
          player22ab=player22ab+1
      elif batterUp2==2:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p3)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=3
          player23hits=player23hits+1
          player23ab=player23ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player23rbi=player23rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p3)/2<pitch2<obp2p3: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=3
            player23walkhbp=player23walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player23rbi=player23rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=3
            player23ab=player23ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=3
          player23ab=player23ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player23rbi=player23rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=3
          player23ab=player23ab+1
      elif batterUp2==3:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p4)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=4
          player24hits=player24hits+1
          player24ab=player24ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player24rbi=player24rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p4)/2<pitch2<obp2p4: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=4
            player24walkhbp=player24walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player24rbi=player24rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=4
            player24ab=player24ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=4
          player24ab=player24ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player24rbi=player24rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=4
          player24ab=player24ab+1
      elif batterUp2==4:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p5)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=5
          player25hits=player25hits+1
          player25ab=player25ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player25rbi=player25rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p5)/2<pitch2<obp2p5: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=5
            player25walkhbp=player25walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player25rbi=player25rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=5
            player25ab=player25ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=5
          player25ab=player25ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player25rbi=player25rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=5
          player25ab=player25ab+1
      elif batterUp2==5:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p6)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=6
          player26hits=player26hits+1
          player26ab=player26ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player26rbi=player26rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p6)/2<pitch2<obp2p6: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=6
            player26walkhbp=player26walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player26rbi=player26rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=6
            player26ab=player26+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=6
          player26ab=player26ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player26rbi=player26rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=6
          player26ab=player26ab+1
      elif batterUp2==6:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p7)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=7
          player27ab=player27ab+1
          player27hits=player27hits+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player27rbi=player27rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p7)/2<pitch2<obp2p7: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=7
            player27walkhbp=player27walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player27rbi=player27rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=7
            player27ab=player27ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=7
          player27ab=player27ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player27rbi=player27rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=7
          player27ab=player27ab+1
      elif batterUp2==7:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p8)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=8
          player28hits=player28hits+1
          player28ab=player28ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player28rbi=player28rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p8)/2<pitch2<obp2p8: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=8
            player28walkhbp=player28walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player28rbi=player28rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=8
            player28ab=player28ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=8
          player28ab=player28ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player28rbi=player28rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=8
          player28ab=player28ab+1
      else:
        pitch2=random.randint(1,1000) #getting a random integer to compare against other stats
        error21=random.randint(1,1000) #getting a number to compare against error stat
        if pitch2<(pitching1+av2p9)/2: #this will give a base hit to player at bat
          menonbase2=menonbase2+1 #gives us a baserunner
          hits4=hits4+1 #gives us a hit in the inning
          hits2=hits2+1 #team 1 gets a hit in the game
          hits22=hits22+1 #team 1 gets a hit in the game
          atbats2=atbats2+1#at bat counter increases
          atBat2=9
          player29hits=player29hits+1
          player29ab=player29ab+1
          if menonbase2>3: #gives a run if bases are loaded
            score2=score2+1
            inningscore2=inningscore2+1
            player29rbi=player29rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
        elif (pitching1+av2p9)/2<pitch2<obp2p9: #not a hit but not an out
          ballplay2=random.randint(1,2) #taking a number to see if ball is in play
          if ballplay2<2: #ball is not in play, batter is walked or hit by pitch
            menonbase2=menonbase2+1
            walkorhbp2=walkorhbp2+1
            inninghbp2=inninghbp2+1
            atbats2=atbats2
            atBat2=9
            player29walkhbp=player29walkhbp+1
            if menonbase2>3:
              score2=score2+1
              inningscore2=inningscore2+1
              player29rbi=player29rbi+1
            else:
              score2=score2
              inningscore2=inningscore2
          else:
            outs2=outs2+1
            atbats2=atbats2+1
            atBat2=9
            player29ab=player29ab+1
        elif 1000-error21<error1:
          error111=error111+1
          menonbase2=menonbase2+1
          inningerror1=inningerror1+1
          atbats2=atbats2+1
          atBat2=9
          player29ab=player29ab+1
          if menonbase2>3:
            score2=score2+1
            inningscore2=inningscore2+1
            player29rbi=player29rbi+1
          else:
            score2=score2
            inningscore2=inningscore2
            inningerror1=inningerror1
        else:
          outs2=outs2+1
          atbats2=atbats2+1
          atBat2=9
          player29ab=player29ab+1
    if score1-score2>=5:
      print"Team 2 Bring in a relief pitcher"
      print"Who is your relief pitcher?"
      pitcher22=raw_input()
      print pitcher22,"average against?"
      pitching2=input()
    if inning==9:
      if score2-score1<=3 and score2-score1>0:
        print"Team 2 Bring in your closer."
        print"Whos is your closer?"
        pitchercloser2=raw_input()
        print pitchercloser2,"average against?"
        pitching2=input()
    print"Inning:",inning
    print"Runs scored Red Sox:",inningscore1,"/Hits:",hits3,"/Walked or Hit by Pitch:",inninghbp1,"/Errors:",inningerror1
    print""
    print"Runs scored Yankees",inningscore2,"/Hits:",hits4,"/Walked or Hit by Pitch:",inninghbp2,"/Errors:",inningerror2
    inning=inning+1
  print"Final score"
  print""
  print"Red Sox:",score1,"/Hits:",hits1,"/Errors:",error111,"/Team Batting Average:",hits11/atbats1
  print""
  print"Yankees:",score2,"/Hits:",hits2,"/Errors:",error222,"/Team Batting Average:",hits22/atbats2
  print""
  print"Individual Player Stats"
  print""
  print"Team One"
  print player11,"Hits:",player11hits,"/At bats:",player11ab,"/RBI:",player11rbi
  print player12,"Hits:",player12hits,"/At bats:",player12ab,"/RBI:",player12rbi
  print player13,"Hits:",player13hits,"/At bats:",player13ab,"/RBI:",player13rbi
  print player14,"Hits:",player14hits,"/At bats:",player14ab,"/RBI:",player14rbi
  print player15,"Hits:",player15hits,"/At bats:",player15ab,"/RBI:",player15rbi
  print player16,"Hits:",player16hits,"/At bats:",player16ab,"/RBI:",player16rbi
  print player17,"Hits:",player17hits,"/At bats:",player17ab,"/RBI:",player17rbi
  print player18,"Hits:",player18hits,"/At bats:",player18ab,"/RBI:",player18rbi
  print player19,"Hits:",player19hits,"/At bats:",player19ab,"/RBI:",player19rbi
  print""
  print"Team Two"
  print player21,"Hits:",player21hits,"/At bats:",player21ab,"/RBI:",player21rbi
  print player22,"Hits:",player22hits,"/At bats:",player22ab,"/RBI:",player22rbi
  print player23,"Hits:",player23hits,"/At bats:",player23ab,"/RBI:",player23rbi
  print player24,"Hits:",player24hits,"/At bats:",player24ab,"/RBI:",player24rbi
  print player25,"Hits:",player25hits,"/At bats:",player25ab,"/RBI:",player25rbi
  print player26,"Hits:",player26hits,"/At bats:",player26ab,"/RBI:",player26rbi
  print player27,"Hits:",player27hits,"/At bats:",player27ab,"/RBI:",player27rbi
  print player28,"Hits:",player28hits,"/At bats:",player28ab,"/RBI:",player28rbi
  print player29,"Hits:",player29hits,"/At bats:",player29ab,"/RBI:",player29rbi
def currentBatter1(atBat1):
  batterUp1=atBat1%9
  return batterUp1
def currentBatter2(atBat2):
  atBat2=atBat2+1
  batterUp2=atBat2%9
  return batterUp2

