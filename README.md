# Bhilwara-CodeLab
Bhilwara CodeLab official website

## Guidelines to contribute
1. Fork into the repository first by clicking on the upper right icon
2. Clone the forked repository by ```git clone https://github.com/<username>/Bhilwara-CodeLab.git```
3. In order to update the forked repo in your system timely, first set ```git remote add upstream https://github.com/Bhilwara-CodeLab/Bhilwara-CodeLab.git```
4. Timely fetch the upstream before making any commit by ```git fetch upstream```
5. Make sure you are on the master branch ```git checkout master```
6. Let say you modify the existing ```a.txt``` and add a new ```b.txt```
7. ```git add a.txt b.txt```
8. ```git commit -m "commit message"```
9. Now to apply your commits on the top of the fetched upstream master, use ```git rebase upstream/master```
10. Now to push to your own forked repo, use ```git push -f origin master```
11. Now ```create a new pull request``` and send it for review

## License
Bhilwara-CodeLab is licensed under the MIT License. Please read more about the [LICENSE](https://github.com/Bhilwara-CodeLab/Bhilwara-CodeLab/blob/master/LICENSE)
