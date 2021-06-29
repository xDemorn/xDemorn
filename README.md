
# \<Hello World> 👋

My name is **Mikolaj Jaworski** and I'm a Junior **Front End Developer**, **Mobile Apps Developer** and **Game Developer** with a 2 year experience.

I'm searching for a job in the city of **Girona** (in Spain, Catalonia) or nearby.
On my free time I'm working on a simple 2D game called **Spater**, which is a top down space shooter based on **Warblade**, which I played a lot when I was younger.

I have 2 years experience with **Angular** and **TypeScript** with many projects that I worked with.

```js
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

  user: User;
  status: Status;
  skills: Skill;

  dev: Developer;

  constructor() { }

  ngOnInit(): void {

    this.user = new User('Mikolaj', 'Jaworski');

    this.status = {
      "is_online": true,
      "learning": [HTML5, CSS3, Angular, TypeScript],
      "interests": [Movies, Gaming, 'V Shows, Zombies, Programming, Learning]
    }

    this.skills = {
      "languages": [HTML5, CSS3, JavaScript, TypeScript, Java, C#, JSON, MySQL],
      "ide": [VisualStudioCode, Netbeans, AndroidStudio, Unity, UnrealEngine],
      "frameworks": [Angular, Bootstrap, NodeJS, ReactNative],
      "os": [Windows, Linux, Android],
      "others": [MicrosoftWord, MicrosoftExcel, Git, GitHub]
    }

    document.write(status, skills);

    this.dev = new Developer(user);

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

<img alt="twitter" src="https://img.shields.io/badge/AMD-Radeon_RX_5700_XT-ED1C24?style=for-the-badge&logo=amd&logoColor=white" />
<img alt="twitter" src="https://img.shields.io/badge/AMD-Ryzen_7_3800X-ED1C24?style=for-the-badge&logo=amd&logoColor=white" />

### Laptop

- Mainly only for education and work, sometimes for netflix and youtube.

<img alt="twitter" src="https://img.shields.io/badge/Windows-MSI_Prestige_15_A10SC-0078D6?style=for-the-badge&logo=windows&logoColor=white" />

## Contact

Feel free to contact me with any of the following platforms.

<a href="mailto:jaworski.miki98@gmail.com" >
<img alt="linked-in" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/mikolaj-jaworski-developer/" >
<img alt="linked-in" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="https://twitter.com/miki_jaworski" >
<img alt="twitter" src="https://img.shields.io/badge/twitter-%231DA1F2.svg?&style=for-the-badge&logo=twitter&logoColor=white" />
</a>
<a href="https://steamcommunity.com/id/xdemorn/" >
<img alt="twitter" src="https://img.shields.io/badge/Steam-000000?style=for-the-badge&logo=steam&logoColor=white" />
</a>
<a href="https://xdemorn.itch.io/" >
<img alt="twitter" src="https://img.shields.io/badge/Itch.io-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white" />
</a>
<a href="https://dev.to/xdemorn" >
<img alt="twitter" src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white" />
</a>

Do you like what you see? Consider droping a follow!

<img alt="Language Stats" src="https://img.shields.io/github/followers/xdemorn.svg?style=social&label=Follow&maxAge=2592000" />

Made with ❤️ and internet searches.

# \</Hello World> 👋
