
![ alt text](https://img.shields.io/twitter/follow/xRadeCoding?logo=twitter&amp;style=for-the-badge)

```Java
public class Kenji extends GitHubUser {

  public Kenji() {
    super("xRadeCoding", "The Belgium");

    this.addLanguage("Java", "Python", "C", "C++", "C#", "Javascript", "LUA", "PHP", "HTML", "CSS");
    this.addExperience("ZortusRP", "MoonMC", "SaturnusMC", "GappleNetwork");
  }
}

public abstract class GitHubUser {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public GitHubUser(String username, String country) {
      this.name = username;
      this.country = country;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}
```
![Github stats](https://github-readme-stats.vercel.app/api?username=xRadeCoding&amp;theme=dark&ampg&show_icons=true)
![Top talen](https://github-readme-stats.vercel.app/api/top-langs/?username=xRadeCoding&amp;theme=dark&amp;count_private=true)
