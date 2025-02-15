
# \<Hello World> 👋

My name is **Mikolaj Jaworski** and I'm a **Front End Developer**, **Mobile Apps Developer** and **Game Developer**.

I have 6+ years experience with **Angular**, 2+ years with React and 1+ year with ArcGIS Experience Builder.

```ts
import { Component, OnInit } from '@angular/core';
import { User } from '@models/user.model';
import { Status } from '@models/status.model';
import { Skill } from '@models/skill.model';
import { Developer } from '@models/developer.model';

@Component({
  selector: 'app-readme',
  templateUrl: './readme.component.html',
  styleUrls: ['./readme.component.scss']
})

export class ReadMeComponent implements OnInit {

  private user: User;
  private status: Status;
  private skills: Skill;

  private dev: Developer;

  constructor() { }

  ngOnInit(): void {

    this.user = new User('Mikolaj', 'Jaworski');

    this.status = {
      is_online: true,
      learning: [ 'HTML5', 'CSS3', 'Angular', 'TypeScript' ],
      interests: [ 'Movies', 'Gaming', 'TV Shows', 'Zombies', 'Programming', 'Learning' ]
    }

    this.skills = {
      languages: [ 'HTML5', 'CSS3', 'JavaScript', 'TypeScript', 'Java', 'C#', 'JSON', 'MySQL', 'C++' ],
      ide: [ 'Visual Studio Code', 'Netbeans', 'Android Studio', 'Unity', 'Unreal Engine' ],
      frameworks: [ 'Angular', 'Bootstrap', 'NodeJS', 'React Native' ],
      os: [ 'Windows', 'Linux', 'Android' ],
      others: [ 'Microsoft Word', 'Microsoft Excel', 'Git', 'GitHub' ]
    }

    this.dev = new Developer(this.user);
    this.dev.updateStatus(this.status);
    this.dev.addSkills(this.skills);
    
    this.dev.writeDataInDocument(document);

    while(dev.isCoding() && dev.isStuck()) {
      dev.openBrowser();
      dev.openStackOverFlow();
      dev.pasteCodeInIde();
      dev.feelProfessional();
    }
}
```

## My Workspaces

### PC Master Race

- Mainly for gaming and game developing.

<img alt="twitter" src="https://img.shields.io/badge/NVIDIA-RTX_3090_FE-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
<img alt="twitter" src="https://img.shields.io/badge/AMD-Ryzen_7_5800X3D-ED1C24?style=for-the-badge&logo=amd&logoColor=white" />

### Laptop

- Mainly for school, sometimes for netflix, youtube and some music.

<img alt="twitter" src="https://img.shields.io/badge/macOS-MacBook_Air_15-0078D6?style=for-the-badge&logo=windows&logoColor=white" />

## Contact

Feel free to contact me with any of the following platforms.

<a href="mailto:jaworski.miki98@gmail.com" >
<img alt="linked-in" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/mikolaj-jaworski-developer/">
<img alt="linked-in" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://twitter.com/miki_jaworski">
<img alt="twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />
</a>
<a href="https://steamcommunity.com/id/xdemorn/">
<img alt="twitter" src="https://img.shields.io/badge/Steam-000000?style=for-the-badge&logo=steam&logoColor=white" />
</a>
<a href="https://xdemorn.itch.io/">
<img alt="twitter" src="https://img.shields.io/badge/Itch.io-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white" />
</a>
<a href="https://dev.to/xdemorn">
<img alt="twitter" src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" />
</a>

Made with ❤️ and internet searches.

# \</Hello World>
