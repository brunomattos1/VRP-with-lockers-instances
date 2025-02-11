# Instances file structure:
## VRPL/VRPLTW

NAME: nXwYlZ_id.vrpl

CUSTOMERS: number of customers

LOCKERS: number of lockers (number of costumers / 10)

RADIUS: coverage radius

CUSTOMER_SECTION

id x y beginTimeWindow endTimeWindow demand

...

LOCKERS_SECTION

id x y beginTimeWindow endTimeWindow 0 (depot)

id x y beginTimeWindow endTimeWindow capacity

...

## VRPPSDL

I: number of customers

F: number of lockers

T: maximum duration

M: number of vehicles

delta: allocation cost

gamma: vehicle cost

id x y beginTimeWindow endTimeWindow serviceTime capapcity (= 0 for customers/depot, > 0 for lockers)

## VRPDA

Name:

name of the instance

sNum:

number of lockers

kNum:

number of customers

m:

number of vehicles

Lambda:

routing/allocation factor (\lambda * routing_{cost} + (1-\lambda) * allocation_{cost}

Q:

vehicle capacity

d:

demand section

s2s:

locker to locker distance

k2s:

customer to locker distance

Coordination of Sites:

id x y

...

Coordination of Customers:

id x y

