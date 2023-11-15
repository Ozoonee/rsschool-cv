# Alexandr Sokolov

---

## Contact info:
- **Address:** Russia, Nizhny Novgorod region, Kstovo town

- **e-mail:** sokolov.alexander.1987@gmail.com

- **Phone:** +7904***3564

---

## Social media:
- **Github:** https://github.com/Ozoonee

- **Discord:** Mirandola#8721

---

## About me:
> *I work an energy company as an engineer. I am fond of programming: I studied Java, Python, now I am interested in learning JS. In my free time I play the guitar, watch movies, and of course I study programming languages. I want to connect my future with the development of software products.*

---

## My skills:
1. **Java:**
- *Spring ,*
- *Maven ,*
- *Gradle ,*
- *Tomcat .*
2. **JavaScript Basic:**
- *DOM API.*
3. **Postman.**
4. **SQL:**
- *MS SQL ,*
- *PostgreSQL.*
5. **Git, GitHub.**
6. **HTML5, CSS, Markdown.**
7. **VS Code, IntelliJ IDEA.**
8. **OS Windows, Linux.**

---

## Code example:
>[My solution kata "RGB To Hex Conversion" from codewars.com:](https://www.codewars.com/kata/513e08acc600c94f01000001)
```
function rgb(r, g, b){
    let currentValues;
    currentValues = [r, g, b].map(el =>{
        if (el<0) {
            return el=0
        }
        else if(el>255){
            return el=255
        }
        else return el
    }) 
    let result;
    result = currentValues.map(el =>{
        return (el.toString(16).split("").length)<2 ?
         '0'+el.toString(16) : 
         el.toString(16)
    })
    return result.join("").toLocaleUpperCase()
}
```

---

## Languages:
- Russian
- English (A2)