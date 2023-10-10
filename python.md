
list = [[milk, 100, 110], [bread, 10, 15]]
result = [["magnit", 0] ["azbuka", 0]]

for product in list: 
   magnit_sum = sum([sublist[1] for sublist in list])
   print("Сумма покупок в Магните составляет" + {magnit_sum}")

azbuka_sum = sum([sublist[2] for sublist in list])
   azbuka_sum = sum([sublist[2] for sublist in list])
   print("Сумма покупок в Азбуке составляет" + {azbuka_sum}")

   if magnit_sum < azbuka_sum:
      print("В магните дешевле") {azbuka_sum - magnit_sum})

elif  magnit_sum > azbuka_sum:
   print("В магните дешевле") {magnit_sum - azbuka_sum})
   else: 
      print ("цена покупок в пятерочке и магните одинакова")
   
      for item in list: 
        item[1] = int(input(f"Введите стоимость {item[0]} в магазине магнит")
            item[1] = int(input(f"Введите стоимость {item[0]} в магазине азбука")