# Olga Rakavets-Tureiskaya

### Junior Frontend Developer
***


### **Contact information:**  
**Phone:** +00 000 0000000  
**E-mail:** email@gmail.com

***
### **About Me:**

Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
***


### **Skills and Proficiency:**

+ Html
+ Css
+ Javascript Basics
+ Git Basics
+ Visual Studio Code
+ Adobe Photoshop  

***
### **Code example:**

```function Losuj() {
  for(let i=0;i<3;i++){
    fetch("https://www.themealdb.com/api/json/v1/1/random.php")
      .then((res) => res.json())
      .then((res) => {
        console.log(res);
  
        const strSource = res.meals[0].strMealThumb;
        const newTitle = res.meals[0].strMeal;
        const Source =res.meals[0].strSource
        const Youtube = res.meals[0].strYoutube
        document.getElementsByClassName("new_title")[i].innerText = newTitle;
        document.getElementsByClassName("img_random")[i].src = strSource;
        document.getElementsByClassName("Source")[i].href = Source
        document.getElementsByClassName("Youtube_link")[i].href=Youtube
      });
      }
}

$random_button.addEventListener("click", () => {
    Losuj()
});
```

***

### **Education**

University:
 + Belarusian National University, Sociology
 + Collegium Da Vinci, Frontend developer (Postgraduate)

***
### **Languages:**

+ Belorussian - Native
+ Russian - Native
+ Polish - Upper/post-intermediate
+ English - Beginner (I started learning English.)
