# Welcome-to-open-source-Contributor Guide ✨

## Steps to follow

1. You will first need to install git. Download from [here](https://git-scm.com/downloads).

2. Now head [here](https://github.com/sayandeepmajumdar/Welcome-to-Open-Source-Contributor) and click on the `fork` button.

3. On the next page you will see a `create fork` button, press it.

4. You will land on your forked repo page, here you will see a `<> Code` button marked in green, click on it and copy the url.

5. Open your terminal and type git clone <url you copied> and press enter.

6. Now you will see a folder named `Welcome-to-Open-Source-Contributor`, open it and edit the `README.md` file using any text editor(ex: VScode).

7. Below is a code snippet for reference which you will add in to the README.md file. Inside the `<b> </b>` tag you have to put your name, in the `<href >` tag, you have to place your github profile URL. And you have to place your github profile photo url inside the `src` tag, then in `<p></p>` tag you add your LinkedIn and Twitter handle.

   ```
   <td align="center">
                <a href="https://github.com/sayandeepmajumdar">
                    <img src="https://avatars.githubusercontent.com/u/33932068?v=4" width="100px;" alt="Sayandeep Majumdar"/>
                    <br />
                    <sub><b>Sayandeep Majumdar</b></sub>
                </a>
                <p align="center">
                    <a href="https://twitter.com/mesayandeep">
                        <img height="40" src="https://cdn-icons-png.flaticon.com/512/4096/4096132.png" alt="Sayandeep Majumdar"/>
                    </a>
                    <a href="https://www.linkedin.com/in/connectwithsayandeep/">
                        <img height="40" src="https://user-images.githubusercontent.com/46517096/166973395-19676cd8-f8ec-4abf-83ff-da8243505b82.png" alt="Sayandeep Majumdar"/>
                    </a>
                </p>
            </td>
   ```

8. Now save your changes and exit the editor, type `git add .`, then `git commit -m "<your name> - from <country name>"` and lastly `git push origin master`.

9. Go to your forked repo page, `sync` your fork and then there you will see a button in green which says `Open pull request`, press it and in the comments section type "Adding my name to contributor list" and press on `create pull request`.

10. You have created a pull request, wait for review and merge it.
