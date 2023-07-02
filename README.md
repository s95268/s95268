<h2 align="center"><a href="https://t.me/wepico">Pico - 🐧</a></h2>
</br>


```cs
public class WePico
{
    public static Tuple<string, string, string> Contact()
    {
        string Discord = "wepico_";
        string Telegram = "t.me/wepico";
        string Website = "GoSec.me";

        return new Tuple<string, string, string>(Discord, Telegram, Website);
    }

    public static Tuple<string, List<string>, int, string> Me()
    {
        string Name = "S...";
        List<string> Speak = new List<string> { "French", "Arabic", "Spanish", "English" };
        int Age = 17;
        string Year = "2005";

        return new Tuple<string, List<string>, int, string>(Name, Speak, Age, Year);
    }

    public static Tuple<Dictionary<string, List<string>>, List<string>, List<string>> Dev()
    {
        Dictionary<string, List<string>> Code = new Dictionary<string, List<string>>
        {
            { "Pro", new List<string> { "Golang", "Python", "C#", "Lua", "JavaScript" } },
            { "Medium", new List<string> { "C", "C++" } }
        };

        List<string> Devs = new List<string> { "Backend", "Software", "Frontend (BAD)" };
        List<string> Editor = new List<string> { "VSCode", "CLion", "Visual Studio" };

        return new Tuple<Dictionary<string, List<string>>, List<string>, List<string>>(Code, Devs, Editor);
    }
}
```


<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=golang,python,cs,lua,js" />
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,cpp" />
  </a>
</p>

<h2 align="center">Stats </h2>

<p href="https://t.me/wepico" align="center">
    <img alt="" src="https://github-readme-stats.vercel.app/api?username=WePico&theme=tokyonight&show_icons=true">
</p>
