Refer to README.md of each individual programming language folders for steps to execute sample scripts.

<b>Prerequisite: </b>
  * npm should be installed.
  * Set your Perfecto credentials for the following environmental variables: 
    * cloudName
    * securityToken

<b>Note: </b>
* Regarding cloudName - (e.g. demo is the cloudName of demo.perfectomobile.com).
* Regarding securityToken - Follow this article: https://developers.perfectomobile.com/display/PD/Generate+security+tokens


<b>Steps for running Native Sample in terminal/ command prompt:</b></br>
1. Follow the prerequisites inside README.md of each individual programming language folders.
2. Run `npm install` from Samples folder
3. Run `npm install -g grunt`
4. Run `npm run replace`
5. Run the following language specific command for executing iOS & Android native app:
   *  Java: `npm run njava`
   *  Ruby: `npm run nruby` 
   *  Javascipt: `npm run njavascript`  
   *  Python: `npm run npython`