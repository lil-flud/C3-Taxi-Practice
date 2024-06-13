# Drive the taxi!!

# While in drive you should be able to:

    - Make right and left turns with "R" and "L" respectively.
      -- R & L should just print out that you made a turn.
    - Hit the brakes with "B".
    - Hit the gas with "G".
    - Put it in park with "P".

# Gas max is 95, min is 0.

# Hitting the gas should increase your speed by 5.

# Hitting the breaks should decrease your speed by 5.

# Should only be able to be put in park when fully stopped. (Speed at 0.)

# While in park you should be able to:

    - Put the car in drive with "D".
    - Pick up a person with "PU".
    - Drop off a person with "DO".

# Print out should look like:

```
Gear: Park
Passenger/s: No
> PU

Gear: Park
Passenger/s: Yes
> D

Gear: Drive
Speed: 0mph
Passenger/s: Yes
> G

Gear: Drive
Speed: 5mph
Passenger/s: Yes
> L

You have made a left turn!

Gear: Drive
Speed: 5mph
Passenger/s: Yes
> B

Gear: Drive
Speed: 0mph
Passenger/s: Yes
> P

Gear: Park
Passenger/s: Yes
> DO

Gear: Park
Passenger/s: No
> quit
```

# If you want to make it more difficult:

- Add the ability to take in a destination when picking up a passenger.
