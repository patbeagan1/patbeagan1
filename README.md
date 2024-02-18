<p align="center">
<img width=60% src="https://user-images.githubusercontent.com/10187351/153775546-556224c7-e4ee-470d-9073-11c310021ac4.png" />
</p>

### Hi there 👋

I'm a software engineer - who currently works as an Android developer. <img src="https://icons.iconarchive.com/icons/cornmanthe3rd/plex-android/72/android-icon.png" height="20" /> 

I enjoy learning new frameworks and technologies, and incorporating learnings from them into my work. Check out all of my projects here: 

<!--- 
vvv Just the urls, as list items
curl https://api.github.com/users/patbeagan1/repos | jq '.[].html_url' | tr '"' ' ' | sed 's/^/-/'
-->
```sh
curl https://api.github.com/users/patbeagan1/repos |
  jq '.[] | {url: .html_url, description: .description}' |
  grep -vE '{|}' |
  sed 's/"//g' |
  sed 's/url:/\n###/g' |
  sed 's/description://g'             
```

I currently work with 
- Kotlin / Rust
- Python / Deno
- Zsh

## Featured projects
- **Desktop Apps**
  - https://github.com/patbeagan1/ConsoleVision
  - https://github.com/patbeagan1/B20-Game-Server
  - https://github.com/patbeagan1/AggronRssReader 
  - https://github.com/patbeagan1/FamilyTreeGenerator
- **Web Apps**
  - https://github.com/patbeagan1/Calendar 
- **Command line tools**
  - https://github.com/patbeagan1/pretty_ip 

