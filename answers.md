# Solutions sheet

Submit your final query after each iteration:

## Iteration 1

db.users.find({}, {name: 1, _id: 0})

## Iteration 2

db.users.find({ hasInsurance: true})

## Iteration 3

db.users.find({ age: { $gte: 18}})

## Iteration 4

db.users.find({ age: { $gte: 18}})

## Iteration 5

db.users.find({ age: { $gte: 18}})

## Iteration 6

db.users.find({ age: { $gte: 18}})

## Iteration 7

db.users.updateOne({ name: "Marissa Geller"}, {$set: {email: "marissa@hotmail.com"}})

## Iteration 8

db.users.updateMany({ country: "UK"}, {$set: {currency: "pounds"}})

## Iteration 9

db.users.updateMany({ country: "UK"}, {$set: {currency: "pounds"}})

## Iteration 10

db.users.updateMany({ country: "UK"}, {$set: {currency: "pounds"}})
