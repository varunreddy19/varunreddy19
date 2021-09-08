# assignment2-pathuri

# Varun Reddy Pathuri
### My Favourite location is Hyderabad in India

**Hyderabad** is rich in Heritage and culture. It has amazing places to see and great restaurents to eat like the world famous __Paradise Biryani__. I love this city beacuse I had studied in this city and spent those years full of joy.

### Directions to travel to Hyderabad

1. Drive from Maryville to Kansas city Airport.
2. Take a flight from Kansas city to Chicago.
3. Take a international flight from Chicago to Delhi.
   1. Onboard a domestic flight from Delhi to Hyderabad Airport.
   2. Book  a cab from Hyderabad airport to Hyderabad City.

### Items to carry for the trip
* Clothes
  * T-shirts
  * Shirts
  * Jeans and Trackpants
* Bodycare
  * Brush
  * soap
* Shoes
* Camera
* Travel bags


**[About Me](AboutMe.md)**

---

### Delicious Items to try in Hyderabad

I recommend to try these Food items which are listed below

| Food/Drink Item | Location | Expected Price |
| --- | --- | --- |
| Chicken Biryani | Bawarchi | Rs 350 |
| Mutton Biryani | Shah Ghose | Rs 550 |
| Paneer Butter Dosa | Gachibowli | Rs 150 |
| Apricot Delight | spicy venue | Rs 200 |

---

### Plithy Quotes

> "No problem can be solved from the same level of consciousness that created it" - *Albert Einstein*<Br>
> "All that glitters is not gold" -*William Shakespeare*

---

### 

>The Fibonacci numbers are the numbers in the following integer sequence.
>0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, ……..
>In mathematical terms, the sequence Fn of Fibonacci numbers is defined by the recurrence relation 
>Fn = Fn-1 + Fn-2
>with seed values 
>F0 = 0 and F1 = 1.

[Click here to know more about Fibanacci numbers](https://www.geeksforgeeks.org/program-for-nth-fibonacci-number/)

```
pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}

```
[Code Source](https://cp-algorithms.com/algebra/fibonacci-numbers.html)

