<h1 align="center">
The Outputs 📤
</h1>

<h2>
1. Challenge Task
</h2>

```bash
QUESTION 1
The number of Indofood products: 7

QUESTION 2
Indofood Products:
1. mie goreng
2. mie goreng cabe hijo
3. mie goreng rendang
4. Indomilk
5. Pepsi
6. Citato bbq
7. Qtela Original

QUESTION 3
Available beverage products:
1. Avocado delight: Rp.10000
2. Indomilk: Rp.20000
3. Pepsi: Rp.20000

QUESTION 4
Indofood snack products
1. Citato bbq
2. Qtela Original

QUESTION 5
Products with the same description!
kopi dalam botol: 3 products
1. Avocado delight
2. Tiramisu Bits
3. Mocainno
Cemilan kentang goreng: 2 products
1. Ayam bakar
2. Salted Egg
```

<h2>
2. Javascript Introduction
</h2>

```bash
Task 2
Average: 84.5
Grade: B

Task 3
1 2 3 4 5 6
1 2 3 4 5
1 2 3 4
1 2 3
1 2
1

Task 4
 {
  id: 1,
  name: 'Oktavian Dwi Putra',
  username: 'Bret',
  email: 'oktavian.dwiputra@gmail.com',
  address: {
    street: 'Kulas Light',
    suite: 'Apt. 556',
    city: 'Gwenborough',
    zipcode: '92998-3874'
  }, {
  phone: '1-770-736-8031 x56442',
  website: 'hildegard.org',
  hobby: 'Playing football'
}

Street & City
 Street: Kulas Light
 City: Gwenborough
```

<h2>
3. Searching Name
</h2>

```bash
# Call the function
searchingName("ol", 4, matchingName)
```

```bash
# The result
[ 'Carol', 'Caroline', 'Carolyn', 'Olivia' ]
```

<h2>
4. Seleksi Nilai
</h2>

```bash
# Call the function
const startNumber = 10
const endNumber = 90
const dataArray = [1,3,90,22,35,67,94,40]

seleksiNilai(startNumber, endNumber, dataArray)
```

```
# The result
[ 22, 35, 40, 67, 90 ]
```

<h2>
5. Cek Hari Kerja
</h2>

```bash
# Call the function
cekHariKerja('senin')
  .then(cek => {
    console.log(`Hari ${cek} adalah hari kerja`)
}).catch(error => {
    console.log(error)
})
```

```bash
# The result
Hari senin adalah hari kerja
```

<h2>
6. Get Month
</h2>

```bash
# Call the function
getMonth(showMonth)
```

```
# The result
[
  'Januari',   'Februari',
  'Maret',     'April',
  'Mei',       'Juni',
  'Juli',      'Agustus',
  'September', 'Oktober',
  'November',  'Desember'
]
```

<h2>
7. Is Month Name
</h2>

```bash
# Call the function
isMonthName('january')
  .then(result => {
    console.log(`${result} is the name of the month`)
}).catch((error) => {
    console.log(error)
})
```

```
# The result
January is the name of the month
```

<h2>
8. Fetch Method
</h2>

```bash
# Call the function
fetch('https://jsonplaceholder.typicode.com/users')
  .then(response => response.json())
  .then(data => {
    data.forEach(user => {
      console.log(user.name)
    })
  })
  .catch(error => console.log(error))
```

```
# The result
Leanne Graham
Ervin Howell
Clementine Bauch
Patricia Lebsack
Chelsey Dietrich
Mrs. Dennis Schulist
Kurtis Weissnat
Nicholas Runolfsdottir V
Glenna Reichert
Clementina DuBuque
```

<h2>
9. Palindrome Check
</h2>

```bash
# Call the function
palindromeCheck('Katak')
```

```bash
# The result
Palindrome
```

<h2>
10. Reverse Words
</h2>

```bash
# Call the function
reverseWords('Saya Belajar Javascript')
```

```bash
# The result
Javascript Belajar Saya
```

<h2>
11. Fazzfood
</h2>

<p align="center"><img src="./advanced-function/assets/fazzfood.png" width=60% alt="fazzfood" /></p>

```bash
# Call the function
fazzFood(120000, 'FAZZFOOD50', 10, true)
```

```bash
# The result
Price: 120000
Discount: 50000
Delivery Fee: 29000
Tax: 6000
Sub-Total: 105000
```

<h2>
12. Divide and Sort
</h2>

<p align="center"><img src="./advanced-function/assets/divide-and-sort.png" width=60% alt="Divide and sort" /></p>

```bash
# Call the function
divideAndSort(2980878096087544)
```

```bash
# The result
2897886944578
```
