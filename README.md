### Hi

My name is Jonathan Fischer and I'm a 5th year PhD student at Johns Hopkins, doing computational modeling in the lab of Dr. Margaret E. Johnson.

```julia
abstract struct PhDStudent end

@kwdef mutable struct JonathanFischer <: PhDStudent
  languages = ["julia", "python", "mathematica", "matlab"]
  interests = ["evolutionary algorithms", "optimization", "language models"]
  age = 28 #old now...
  should_hire = true
end
```
