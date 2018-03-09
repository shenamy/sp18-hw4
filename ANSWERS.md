## Questions

1. What is the difference between `new` and `create` for a model?
New creates an instance of a model that is not saved to the database, so it is only saved locally, while create saves it to the db.

2. What command followed after with `Cat.new` will emulate the same behavior as `Cat.create`?
Calling save afterwards emulates the same behavior. 

3. What is the default integer column that exists on every table but we did NOT define?
the ID
4. What single line of ruby code can insert a cat with the name "Kira" in the database?
Cat.create(name: "Kira")

5. How did you like this homework in comparison with the previous homeworks?
A lot more difficult, but learned a lot. 