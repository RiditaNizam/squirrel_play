# squirrel_play
CodingBat Python Logic-1

def squirrel_play(temp, is_summer):
  
  if not is_summer and temp >= 60 and temp <= 90:
    return True
  
  elif is_summer and temp >= 60 and temp <= 100:
    return True
  
  else:
    return False
