import requests 

#print(requests.get('https://fakestoreapi.com/')) #    

#print(requests.get('https://fakestoreapi.com/products/1'))

#print(requests.get('https://fakestoreapi.com/products/categories'))

##print(requests.get('https://fakestoreapi.com/products/categories'))

#requests.head('https://fakestoreapi.com/products/categories')

print(requests.get('http://fakestoreapi.com/products'))
r = requests.get('http://fakestoreapi.com/products')
print(r.json())
