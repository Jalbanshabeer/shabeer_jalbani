<!-- Replace YOUR-USERNAME everywhere. Put this file in a repo named exactly YOUR-USERNAME -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Hi%2C%20I'm%20Shabeer%20Jalbani&fontSize=44&fontAlignY=38&animation=fadeIn&desc=CS%20Student%20%7C%20C%2B%2B%20%26%20Java%20%7C%20Web%20Developer&descAlignY=60" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=6EE7FF&center=true&vCenter=true&width=600&lines=Computer+Science+Student+(3rd+Semester);Learning+C%2B%2B+%26+Java+OOP;Building+animated+web+projects;Always+coding%2C+always+learning" alt="Typing animation" />
</p>

## 👨‍💻 About Me

- 🎓 CS student (3rd semester) at **Benazir Bhutto University of Technology and Skill Development, Khairpur Mirs**
- 💻 Learning **C++**, **Java** and **Web Development**
- 🏅 **Google AI Essentials** certified (Coursera)
- 🌐 Building a liquid glass animated portfolio website
- 🚀 Goal: become a skilled software developer

## 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

## 📚 OOP Basics (C++ & Java)

| Concept | Meaning | Simple Example |
|---|---|---|
| **Class & Object** | Blueprint and its real instance | `Car` is the class, `myCar` is the object |
| **Encapsulation** | Hide data, expose it through methods | `private` data + getters/setters |
| **Inheritance** | Child class reuses parent code | `Dog` extends/inherits `Animal` |
| **Polymorphism** | Same method, different behavior | `speak()` differs for `Dog` and `Cat` |
| **Abstraction** | Show only what is necessary | abstract classes / interfaces |

<details>
<summary><b>C++ example</b></summary>

```cpp
#include <iostream>
using namespace std;

class Animal {
protected:
    string name;
public:
    Animal(string n) : name(n) {}
    virtual void speak() { cout << name << " makes a sound\n"; }
};

class Dog : public Animal {
public:
    Dog(string n) : Animal(n) {}
    void speak() override { cout << name << " says Woof!\n"; }
};

int main() {
    Animal* a = new Dog("Tommy");
    a->speak();
    delete a;
}
```
</details>

<details>
<summary><b>Java example</b></summary>

```java
class Animal {
    protected String name;
    Animal(String name) { this.name = name; }
    void speak() { System.out.println(name + " makes a sound"); }
}

class Dog extends Animal {
    Dog(String name) { super(name); }
    @Override void speak() { System.out.println(name + " says Woof!"); }
}

public class Main {
    public static void main(String[] args) {
        Animal a = new Dog("Tommy");
        a.speak();
    }
}
```
</details>

## 🏆 Certificates

| Certificate | Issuer | Date | Verify |
|---|---|---|---|
| **Google AI Essentials** (Specialization, 5 courses) | Google via Coursera | Dec 26, 2025 | [Verify](https://coursera.org/verify/specialization/DQF35WOWB1LM) |
| **Introduction to AI** | Google via Coursera | Dec 26, 2025 | [Verify](https://coursera.org/verify/56F7CUJU8NU3) |
| **Use AI Responsibly** | Google via Coursera | Dec 26, 2025 | [Verify](https://coursera.org/verify/LO6U00I10FND) |

<p>
  <img src="https://img.shields.io/badge/Google%20AI%20Essentials-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Coursera-0056D2?style=for-the-badge&logo=coursera&logoColor=white"/>
</p>

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR-USERNAME&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-USERNAME&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR-USERNAME&theme=tokyonight&hide_border=true" />
</p>

## 📫 Connect With Me

<p>
  <a href="https://github.com/YOUR-USERNAME"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github"/></a>
  <a href="https://linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin"/></a>
  <a href="mailto:your@email.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" />
</p>
