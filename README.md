# Index

0 - Requeriments  
1 - How to start VUE project  

## 0 - Requeriments

At the time of write this file I will use this versions:  
><https://nodejs.org/dist/v14.16.1/node-v14.16.1-x64.msi>  
  
## 1 - How to start VUE project

Go to the folder where you want to create your project and write:
    npm install -g @vue/cli

Check if Vue has been installed:
    vue --version
        @vue/cli 4.5.12

Generate the project:
    vue create vue-learning

For that question select "Default" option:
  
    Vue CLI v4.5.12  
    ? Please pick a preset: (Use arrow keys)  
    Default ([Vue 2] babel, eslint)  
    Default (Vue 3 Preview) ([Vue 3] babel, eslint)  
    Manually select features  
  
With Vue 3 it's possible to have problems with some packages

After that go to the project directory:
    cd vue-learning

Start the server with the project:
    npm run serve

After that you will something like that:
  
    DONE  Compiled successfully in 3896ms

    App running at:
    - Local:   http://localhost:8080/
    - Network: http://192.168.0.15:8080/

    Note that the development build is not optimized.
    To create a production build, run npm run build.

## 2 - Adding new packages

In this example we install vuex:  
>npm install vuex --save