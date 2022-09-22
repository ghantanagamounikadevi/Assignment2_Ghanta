# Assignment2_Ghanta
# Naga mounika devi Ghanta
###### Museum of Science and Industry
The place where oddments display to remind the histoy is museum.<br>Museums provide effective way of learning those are useful to improve the skiils of the students.<br>There are some of the exhibits we dont want to miss in the science museum like **Science Storms**and**Fast forward and inventing the future**.
---
# Directions for to go the Science museum.
1. The Chicago Midway Airport is the nearest of the science museum.
2. We can take right from the airport exit then take U turn.
3. After that take left turn and go staright up to 3KM.
4. Our destination will be at left.
---
---
# Other locations around the museum

* Jackson Park Beach.
* Hyde park
* Frank Lloyd Wright's Robie House

[Aboutme](Aboutme.md)
_ _ _
# Tables
The cities that i recommend to visit in India Vizag , Hyderabad,Agra and Tirupathi.These cities are most attractive places for the turists here you can view like Charminar,TajMahal,RK beach and the famous tirumala balaji temple.
| Name of the city | Location to visit in the city | Amount of the time |
| --- | --- | ---: |
| Vizag | RK beach | 6 |
| Hyderabad | Charminar | 2 |
| Agra | TajMahal | 5 |
| Tirupathi | Balaji temple | 4 |
***
# Quote
> Be there for others, but never leave yourself behind.---*Dodinsky*s
>
> Work Hard dream Big Never Giveup. ---*AL rocker*
 ---
# Code fencing
> How to find Sorting Function in Saas?

[Question](https://stackoverflow.com/questions/71601457/create-arrays-sorted-on-date-timestamps)

```
/// Quick sort
/// @author Sam Richards
/// @param {List} $list - list to sort
/// @return {List}
@function quick-sort($list) {
  $less:  ();
  $equal: ();
  $large: ();

  @if length($list) > 1 {
    $seed: nth($list, ceil(length($list) / 2));

    @each $item in $list {
      @if ($item == $seed) {
        $equal: append($equal, $item);
      } @else if ($item < $seed) {
        $less: append($less, $item);
      } @else if ($item > $SEED) {
        $large: append($large, $item);
      }
    }

    @return join(join(quick-sort($less, $order), $equal), quick-sort($large, $order));
  }

  @return $list;
}
```
[Code snippet](https://css-tricks.com/snippets/sass/sorting-function/)
---