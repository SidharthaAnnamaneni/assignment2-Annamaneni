# assignment2-Annamaneni
# Sidhartha Annamaneni
###### HYDERABAD
Formerly known as The Diamond City and currently known as The Pearl City of India, Hyderabad serves as a joint capital for the states of Andhra Pradesh and the newly formed Telangana. With a very rich culture and history, the city is now growing to be a leading IT center in India along with Bengaluru and Pune. This rich city also gives its visitors a lot of opportunities to create memories and leave them with many reasons to visit again. There are many places to visit here. You can always have a wonderful time no matter what company you have with you, family, relatives, friends, colleagues, anyone.

---

## Travel itinerary to Hyderabad:

1. Take any road commute to Kansas International airport(MCI).
2. Booking flights.
    1. Kansas city (MCI)-IndraGandhi int.airport(DEL).
    2. IndraGandhi int.airport(DEL)-RajivGandhi int.airport(HYD).
3. Use cab to Reach any destination in city.

* places to visit.
    * Charminar 
    * Ramoji film city
    * Ananthagiri Hills
* For foodies
    * Biryani (RTC cross roads)
    * chat (Gokul chat)
    * dosa (Ram ki Bandi)

**[click here to navigate to About Me](AboutMe.md)**

---

## Foods that I suggest to try
The foods I mentioned here are very basic indian cusine food that every one can have but made in authentic style.In india some places are famous for the foods that available over there some of them are:

|  Food Item        |  Location   |  Price  |
|---                |---          |---:     |
|chicken Dum Biryani|  Hyderabad  | 150 INR |
|Idly Sambaar       |  Chennai    |  50 INR |
|Lassi              |  Punjab     |  50 INR |
|Vada Pav           |  Mumbai     |  20 INR |

---

## Quotes that inspire me

>Dream is not which you see while sleeping,it is something that does not let you sleep
-*Dr.A.P.J.Abdul Kalam*
>Respect is how you treat everyone not just those you want to impress
-*Richard Branson*

***

## Code Fencing
>The shoelace formula or `shoelace algorithm` (also known as Gauss's area formula and the surveyor's formula) is a mathematical algorithm to determine the area of a simple polygon whose vertices are described by their Cartesian coordinates in the plane.The user cross-multiplies corresponding coordinates to find the area encompassing the polygon, and subtracts it from the surrounding polygon to find the area of the polygon within.

Read More: <https://en.wikipedia.org/wiki/Shoelace_formula>

~~~

double area(const vector<point>& fig) {
    double res = 0;
    for (unsigned i = 0; i < fig.size(); i++) {
        point p = i ? fig[i - 1] : fig.back();
        point q = fig[i];
        res += (p.x - q.x) * (p.y + q.y);
    }
    return fabs(res) / 2;
}

~~~

click here for code source: <https://cp-algorithms.com/geometry/area-of-simple-polygon.html>