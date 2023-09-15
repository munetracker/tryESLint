https://chat.openai.com/share/23c43816-1677-4db4-8f93-93ab77ea5041

npm init -y
npm install eslint --save-dev
npx eslint --init

package.json
"scripts": {
  "lint": "eslint .",
  "lint:fix": "eslint . --fix"
}

npm run lint

create .gitignore file