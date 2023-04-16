# Web3.0_task

I created a Class "Car" with private attributes - make, model, year, speed_x, speed_y, fly_speed_z, x, y and z so that they can be accessed only by the member functions of the class.

Within the public access specifier, defined a constructor for easier initialization of variables and better handling of data. Also defined the methods here so that they are accessible everywhere.

Methods -

1. accelerate_x - Updates speed_x according to the given increment.
2. accelerate_y - Updates speed_y according to the given increment.
3. rocket - Updates fly_speed_z according to the given increment.
4. brake_x - Updates speed_x after brake is applied.
5. brake_y - Updates speed_y after brake is applied.
6. brake_z - Updates fly_speed_z after brake is applied.
7. move - Updates position of the car.

Logic - Found the time after which collision will take place, if possible else. Updated coordinates of both cars accordingly. If the coordinates of the cars coincide, then they collide.
