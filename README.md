# exercise-11

#applying percentage discounts for products

preco = float ( input ('qual é o preço do produto? '))
desc = float ( input ('qual a porcentagem do desconto?  '))

print ('o produto que custava R${}, com desconto de {}% sairá por R${:.2f}' .format (preco , desc , (preco /100) * (100 - desc)))
