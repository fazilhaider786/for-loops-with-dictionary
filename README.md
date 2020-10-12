# for-loops-with-dictionary
         students = {     
                 "male": ["Tom", "Charlie", "Harry", "Frank"],     
                 "Female": ["Sarah", "Huda", "Samantha", "Elizabeth"]     
                } 
               for key in students.keys():     
               for name in students[key]:         
               if "a" in name:             
               print(name)
