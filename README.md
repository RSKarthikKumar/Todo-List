# to-do-list
a to-do list fullstack web app deployed on Heroku with MongoDB cloud

author:R.S.Karthik Kumar
## installation & use

If you would like to download the repo and run the app locally on localhost 3000 (or any port you specify), that is also an option.

## Tools, libraries used & why I chose to use it
The following table shows my rationale behind building this app, and why I chose to use the frameworks and tools that I did.

<table>
  <tbody>
    <tr>
        <th>Tool</th>
        <th>Why I chose it</th>
    </tr>
    <tr>
        <td>Node.js</td>
        <td>
            <ul>
                <li>popular and well-documented</li>
                <li>uses JS as main application</li>
                <li>robust framework</li>
            </ul>
        </td>
    </tr>
    <tr>
      <td>Express.js</td>
      <td>makes it easier to handle http requests</td>
    </tr>
    <tr>
      <td>MongoDB cloud</td>
      <td>
        <ul>
          <li>noSQL DBs like MongoDB are easier to scale</li>
          <li>not much inter-document relationships need to be made for the purposes of this app</li>
          <li>well-documented</li>
          <li>free cloud database</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Heroku</td>
      <td>handles a lot of server-side stuff for me and gets rid of a *lot* of headaches</td>
    </tr>
    <tr>
      <td>body-parser</td>
      <td>helps with requests from client-side e.g. add item, delete item</td>
    </tr>
    <tr>
      <td>dotenv</td>
      <td>login security</td>
    </tr>
    <tr>
      <td>ejs</td>
      <td>saves a lot of lines of code, especially given that I need to rewrite the same code so many times when creating new to-do lists</td>
    </tr>
    <tr>
      <td>lodash</td>
      <td>makes string formatting a lot easier</td>
    </tr>
  </tbody>
</table>


