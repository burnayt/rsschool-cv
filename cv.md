# Grekov Grigoriy
# My Contact Info
* **E-mail**: mywork35@yandex.ru
* **GitHub**: [burnayt](https://github.com/burnayt/)
* **Discord**: burnout#3973
 
# About Me
I am a programmer enthusiast and game designer. I enjoy game development (I have 5 prototypes), backend development (I have 2 prototypes) and data analysis (I like to make time series predictions). I started with C Sharp in Unity. Now I know about 5 programming languages and several engines and frameworks. In my spare time I do some modeling.
# Skills
* Unity and **C#**
* Unreal Engine(**C++** and Blueprint)
* **Python**(django, dash)
* **Javascript**
* **Lua** (CoreGames)
* **Blender**
 
# Code Examples
```
function createNode(array, i){  
 if (array[i] === undefined){ return; }
 
 let el = new TreeNode( array[i],
  array[2*i+1] == undefined? undefined : createNode(array, 2*i+1),
  array[2*i] == undefined? undefined : createNode(array, 2*i+2) )
 return el;
 
}
function arrayToTree(array) {    
  return createNode(array, 0);
   
};
```

