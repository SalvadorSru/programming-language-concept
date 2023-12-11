## Estructuras de control

## Condicionales

### IF

(todavía no me decido)

```
    (< condicional >) // if
    ? // true
        asdasd
    ! // false
        asdasd
    ;
```


```

    - IsAdults(age) -> {
        (age > 18) ? {
            ·> "Es mayor de edad"
            !
            ·> "Es menor de edad"
        }
    }

```


### SWITCH

```
    (< key >) -* {
        * (< condicion >) :
        
        * (< condicion >) :
        
        * (< condicion >) :

        *> // default :
    }

    // Devuelve por defecto el valor matcheado

    · number = (1) -* {

        * (1) 
            ·> "One!"
            
        * ( 2 | 3 | 5 | 7 | 11 )
            ·> "This is a prime"
            
        *> "Nothing intereseting"

    } // "One!"
```