
![Frame 49](https://github.com/ImYourMuse/ImYourMuse/assets/97489339/29e5fbb6-f491-46aa-81c7-71c132d9178b)

<p>Hi there!👋 My name is Binh and I'm studying information technology in 2024. I'm passionate about math and 2D games. <a href="http://teamobi.com/home/trang-chu.html" target="_blank"><button style="background-color: transparent; border: none; color: blue; text-decoration: underline; cursor: pointer;">Teamobi's</button></a> <img src="/Teamobi.png" alt="Image" style="width: 3%;" /> game "Avatar💕" has inspired me to explore Unity! </p> 





 



















  
 ```c#
class TheColors : MonoBehaviour
{
    private int self_age = 22;
    private bool self_isStudent = true;
    private string seft_school => "CTU";
    private string self_nationality => "Vietnamese";
    private string[] self_hobbies => new string[] { "Programming", "Music", "Youtube" };
    private string[] self_programming_languages => new string[] { "C#", "JavaScript" };
    private List<string> self_skills = new List<string>();

    private void Start()
    {
       self_skills.Add("C# scripting");
       self_skills.Add("Asset integration");
       self_skills.Add("Game physics");
       self_skills.Add("Performance optimization");
       self_skills.Add("Multiplayer networking");

       InvokeRepeating(() => {
         self_isStudent = (++self_age >= 23) ? false : true;
        }, 365 * 24 * 60 * 60, 365 * 24 * 60 * 60);
    }
}   
```



 
 

<br/>

