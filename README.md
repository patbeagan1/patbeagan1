<p align="center">
<img width=60% src="https://user-images.githubusercontent.com/10187351/153775546-556224c7-e4ee-470d-9073-11c310021ac4.png" />
</p>
<p align="center">
Generated with <a href="https://github.com/patbeagan1/ConsoleVision">ConsoleVision</a>
</p>

### Hi there 👋

I'm a software engineer - who currently works as an Android developer. <img src="https://icons.iconarchive.com/icons/cornmanthe3rd/plex-android/72/android-icon.png" height="20" /> 

I enjoy learning new frameworks and technologies, and incorporating learnings from them into my work. 

I currently work with 
- Kotlin / Rust
- Python / Deno
- Zsh

Check out all of my public projects here: 

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

Note that this is not fully inclusive of the projects that I've published. I have a separate repo, [Open-Source-Requests](https://github.com/patbeagan1/Open-Source-Requests) where anyone can request for me to publish the source code for a tool - rationale included in there. 

## Published projects
- [via Cargo](https://crates.io/users/patbeagan1/)
- [via pip](https://pypi.org/user/patbeagan1/)

<!--
How to publish, per platform

Rust
`cargo publish`, with the correct info in the Cargo.toml file

Python
https://pypi.org/manage/projects/
https://packaging.python.org/en/latest/tutorials/packaging-projects/
-->
