Based on https://gist.github.com/withr/9001831

Username: test  
Password: 123

To run directly from GitHub use:

```
devtools::install_github(c("daattali/shinyjs", "aoles/shinyURL"))
shiny::runGitHub("aoles/shinypass")
```
 
See [here](https://github.com/aoles/shinypass/issues/2#issuecomment-425394037) on how to generate the MD5 password hashes.
