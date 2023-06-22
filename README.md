### Hi there, I'm Romain 👋

<p><em>Computer Science & Engineering student at <a href="https://www.imt-mines-ales.fr/">IMT Mines Alès
</a><img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

[![website](https://img.shields.io/badge/Website-46a2f1.svg?&style=flat-square&logo=Brave&logoColor=white&link=https://rstr.fr/)](https://rstr.fr/)
![](https://visitor-badge.glitch.me/badge?page_id=RomainStorai.RomainStorai)
[![Linkedin: romain-storaï](https://img.shields.io/badge/-Romain-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/romain-storaï/)](https://www.linkedin.com/in/romain-storaï/)

```java
class Romain extends Student {
    
    final String username;
    String location;
    String favoriteLanguage;
    
    public Romain() {
        username = "Romain";
        //location = "France";
        location = "South Korea";
        favoriteLanguage = "Java";
    }
    
    public School[] getSchools() {
        School[] mySchools = new School[2];
        
        String schoolName = "IMT Mines Alès";
        Degree degree = Degree.MASTER_OF_ENGINEERING;
        List<String> subjects = List.of("Computer Science", "Artificial Intelligence", "General Engineering");
        mySchools[0] = new School(schoolName, degree, subjects);

        schoolName = "Seoul National University 서울대학교";
        degree = Degree.MASTER_OF_SCIENCE;
        subjects = List.of("Artificial Intelligence", "Deep Learning", "Natural Language Processing");
        mySchools[1] = new School(schoolName, degree, subjects);
        
        return mySchools;
    }
    
    public String[] getGoals() {
        return new String[] {"Learn new things (blockchain, machine learning, hacking)", "Contribute to OpenSource"};
    }
    
    public boolean isFreeToContact() {
        return true;
    }
}
```

<!--
**RomainStorai/RomainStorai** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
