### Hey there!

My name is Jonathan Fischer and I'm a 4th year PhD student at Johns Hopkins, doing computational modeling in the lab of Dr. Margaret E. Johnson.

```julia
abstract struct PhDStudent end

@kwdef mutable struct JonathanFischer <: PhDStudent
  languages = ["julia", "python", "R"]
  interests = ["evolutionary algorithms", "nonconvex optimization", "language models"]
  age = 26
  should_hire = True
end
```
