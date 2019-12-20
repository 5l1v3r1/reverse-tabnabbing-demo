# Reverse tabnabbing demo

Go to https://htmlpreview.github.io/?https://github.com/EdwinOtten/reverse-tabnabbing-demo/blob/master/vulnerable-page.html to get started.

## Explanation

When visiting the vulnerable page, you see a link to another website which opens in a new tab, as well as a login form. Upon clicking the link to the other website, the original tab gets redirected to a website that looks nearly identical.

## Why is this bad?

An unsuspecting user could go back to the original tab and enter his highly confidential credentials, not knowing he is now on a (potentially) malicious website and everything he does could be logged.
