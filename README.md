# Nicholas Taylor
### Baseball
 Baseball is a great sport to watch on the TV, but even better in person. It is one of the most **competitive** sports, requiring more than just physical strength. I have watched and played baseball since I was less than **10 years** old.

---
### Favorite team and players
Los Angeles Dodgers
1. Gavin Lux
2. Mookie Betts
3. Trayce Thompson

- Toronto Blue Jays
- Boston Red Sox
- Miami Marlins

Link to my AboutMe: [AboutMe](https://github.com/NTaylor29/assignnment2-taylor/blob/main/AboutMe.md)

---
### Countries to visit
I have never been outside the United States, but I can recommend some based on pictures I have seen.
| Country | Reasoning | Days |
| ---     | ----      | ---  |
| Canada  | Cold      | 7    |
| UK      | They talk weird | 5 |
| Mexico  | Cheap     | 14   |
| Italy   | Eiffel Tower | 21 |

---
### Funny Quotes
> If you got a dog, feed it. If you don't, don't. *- Bobby Shmurda*

> Ouch I got shocked. *- probably Benjamin Frankin*

---
### Code Fencing
> I'm trying to retrieve the value from a Custom field as below. It doesn't seem to get any value. Please point out the mistakes in it. [StackOverflow Link](https://stackoverflow.com/questions/66293239/wordpress-how-to-retrieve-custom-field-data-from-the-page)
```
<h3>All Post Meta</h3>

<?php 

  // Get all the data 
  $getPostCustom = get_post_custom(); 

    foreach($getPostCustom as $name=>$value) {

        echo "<strong>" . $name . "</strong>"."  =>  ";

        foreach ($value as $nameAr=>$valueAr) {
                echo "<br />";
                echo $nameAr."  =>  ";
                echo var_dump($valueAr);
        }

        echo "<br /><br />";

    }
?>
```
[Code Snippet](https://css-tricks.com/snippets/wordpress/dump-all-custom-fields/)