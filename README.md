# assignment2-Mathi
# Apurupa Mathi
###### Nandi Hills

It is located in the **South Indian State of Karnataka** and it is famous for **hill of happiness** and it is a destination for hiking and trekking.

---

# Directions for traveling from Maryville to Nandi Hills
1. Book a cab from Maryville to Kansas airport
2. Finish the check-in process through online
   1. Take boarding pass from a self-service Kiosk
   2. Waiting for the flight
   3. Board your Flight
3. Complete your check-out process in Karnataka
    
* Clothes
  * Sweater
  * Shoes
* Cosmetics
  * Make-up
  * Lotions
* Money
* Snacks
  * Choclates
  * Biscuits

[AboutMe](https://github.com/Apurupa-mathi/assignment2-Mathi/blob/main/AboutMe.md)

---

# Table Creation

A table with three columns recommends the some of the best foods that i experienced in india.

| FOOD/DRINK         |     Location      |   Cost    |
|     ---            |       ---         |   ---     |
| Spaghetti Pasta    |     Bukhara       |   $2.99   |
|Creme Frappuccinos  |     Strabucks     |   $5.45   |
|Mozzarella pizza    |     Pizza hut     |   $6.99   |
|Choclate AlmondMilk |    Starbucks      |  $5.45    |

---

# Quotes by Authors

> "Keeping yourself happy is your own responsibility.Do everything that you can,daily." - by
***Rahul Kaushik*** <br>
> "Don't be serious,be sincere." - by
***Chetan Bhagat***

---

# Algorithm on strings
In computer programming, a string is traditionally a sequence of characters, either as a literal constant or as some kind of variable. The latter may allow its elements to be mutated and the length changed, or it may be fixed (after creation). A string is generally considered as a data type and is often implemented as an array data structure of bytes (or words) that stores a sequence of elements, typically characters, using some character encoding. String may also denote more general arrays or other sequence (or list) data types and structures.

Source link - <https://en.wikipedia.org/wiki/String_(computer_science)>

```

long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}

```

source link - <https://cp-algorithms.com/string/string-hashing.html>
