yarn global add firebase-tools
--firebase-tools@13.4.0
firebase login
npx create-react-app firebase-recipes-web-app
console.firebase.google.com
firebase init
yarn build
firebaes deploy
https://fir-recipes-2ec49.web.app

yarn add firebase --exact
--firebase 10.8.1

git remote add origin https://github.com/tim4799/firebase-recipes-web-app.git

Generate personal access token ->github.com -> settings -> Developer settings
Refer to "Git& Github - The Practical Guide", Lesson 71, 72, 73
In Terminal, not VSC
git credential-osxkeychain erase <Enter>
host=github.com <Enter>
protocol=https <Enter>
<Enter>

git push -u origin main
input login name <Enter>
input token <Enter>

firebase init
git push

package.json
"buildDeploy": "yarn build && firebase deploy --only hosting"
yarn buildDeploy