```js
class EfeUCler {
  constructor(...options) {
    this.height = "1.83"
    this.weight = "70"
    this.age = "16"
    this.type = "human"
    this.job = "student"
    this.sex = "male"
  }
}

class CreateMan extends EfeUcler {
  constructor(...options) {
    super(options);
  }
  
  private _eating() {
    void "eating 🥩 🍷"
  }
  
  private _carting() {
    void "carting 🏎️ "
  }
  
  private _coding() {
    void "coding... ❤️"
  }
  
  private _gaming() {
    void "gaming 🎮"
  }
  
  private _sleep(ms) { return new Promise(resolve => setTimeout(resolve, ms)) }
  
  async createDay() {
    this._eating();
    this._carting();
    this._coding();
    this._gaming();
    await this._sleep(18000000);
    
    this.createDay();
  }
}

let EfeUcler = new CreateMan()
EfeUcler.createDay();
```



##  Dostlarım
- ![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
- ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
- ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
- ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
- <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=efeucler3&theme=dark&hide_langs_below=1" /> [![Efe's GitHub stats](https://github-readme-stats.vercel.app/api?username=efeucler3&theme=dark&hide_langs_below=1")](https://github.com/efeucler3/github-readme-stats)
- 
<img src="https://komarev.com/ghpvc/?username=efeucler3&label=Ziyaretçi%20Sayısı&color=723F98" alt="efeucler3"/>
