#Example Code
```
(function main (void)
    (Cow* cow1) ;this is a pointer not an obj
    (Cow* cow2)

    (= Cow1 (new Cow cow1 1)) ;this instantiate a cow obj on the heap
    (= Cow2 (new Cow cow2 4))
    (Cow1 toString)
    (delete cow1)
    (delete cow2)
    (= Cow1 nullptr)
    (= Cow2 nullptr))
(class Cow (private (string name) (int age))
  (public
    (method (Cow (string name) (int age))
      (= this.name name)
      (= age this.age age))
    (method (toString)
      (printf “Name” << name << “age” << age))))
```
