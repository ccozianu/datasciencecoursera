# How to set up R

Deviate from course, use rocker project:
https://rocker-project.org/

Using '''r-base''' for quick console interaction

Course directory is in costin3/learn/Coursera_DataScience/ 
which will be mapped to     /Coursera_DataScience

Docker was started with:
```bash
docker run  -v ${PWD}/learn/Coursera_DataScience/:/Coursera_DataScience --name Coursera_DS_C1_RConsole0 -ti r-base bash -i
```

To get to R in the docker, we take 2 commands, to restart the docker if needed, ad then bash into it and execute R
```bash
    docker start Coursera_DS_C1_RConsole0
    docker exec -it  Coursera_DS_C1_RConsole0 bash -i
    # once iside bash , R is the command
```
