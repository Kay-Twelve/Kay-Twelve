<h2 align="center" style="text-align: center">🔥📚 Always Improving</h2>
<br>
<table align="center" style="width: 100%; border-color: transparent !important;">
  <td>

  ```rust
  pub mod carrer {
      pub enum Training {
          SystemsDeveloper,
          ComputerEnginner
      }

      pub struct Developer<'a> {
          pub name: &'a str,
          _age: i8,
          _training: Training
      }

      impl<'a> Developer<'a> {
          pub fn new(
            name: &str, 
            age: i8, 
            training: Training
          ) -> Developer<'_> {
              Developer {
                  name,
                  _age: age,
                  _training: training
              }
          }
      }
  }
  ``` 

  </td>

  <td>

  ```rust
  fn main() {
      let my_profile = carrer::Developer::new(
          "Kaylan Carlos", 
          24, 
          carrer::Training::ComputerEnginner
      );
      println!(
        "My name is {}. Welcome to my profile!!", 
        my_profile.name
      );
  }
  ``` 

  </td>
</table>
<br>
<h2 align="left">👾 Technologies and tools</h2>
<br>
<div align="center" style="display: inline; text-align: center;">
  <img src="https://img.shields.io/badge/Rust-black?style=for-the-badge&logo=rust&logoColor=#E57324">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white">
  <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue">
  <img src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=GodotEngine&logoColor=white">
  <img src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white">
  <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white">  
</div>
<div align="center" style="display: inline; text-align: center;">
</div>
<br>
<h2 align="left">🧮 Statistics</h2>
<div align="center" style="display: inline;">
    <img height="185em" src="https://github-readme-stats.vercel.app/api?username=Kay-Twelve&theme=algolia&show_icons=true&hide_border=true&count_private=true"/>
    <img height="185em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kay-Twelve&theme=algolia&show_icons=true&hide_border=true&layout=compact"/>
</div> 
  