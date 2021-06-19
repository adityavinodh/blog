---
title: "How to Sign Commits on GitHub"
date: 2021-06-11T23:13:55+05:30
draft: false
summary: "Learn how to sign your commits to verify the authenticity on GitHub"
tags:
  [
    "commits",
    "git",
    "github",
    "sign",
    "signing",
    "gpg",
    "cryptography",
    "authenticity",
  ]
editPost:
  URL: "https://github.com/adityavinodh/blog/tree/main/content"
  Text: "Suggest Changes"
  appendFilePath: true
---

# What is Signing?

Digital signing of any kind of document, email, message, or even your commits on your Git or GitHub repository are very similar to physically signing something using a pen. It is a way to verify the authenticity of the item. In simple terms, it helps us make sure that the item actually originates or comes from the person or author that we think it comes from. Digital signing makes use of cryptographical techniques to generate a public/private key pair. The document or data is signed using the private key which is never shared, and the authenticity can be verified using the public key which can be shared with everyone.

# Why should you sign code on GitHub

When contributing code on large open source projects, sometimes it is important to make sure the repository is secure, and prevent any unauthorized changes. When you make changes, stage them, add the commit, and push the code to the remote repository on GitHub, there is a lot of metadata that is attached along with the actual code. Every commit contains the author's name and email which can be changed. Even though you authenticate using your GitHub username and password or personal access token, it is possible to change your name and email that you use for Git to make commits.

## Proof

I have added the same email to my Git config and my verified email on GitHub. But I have chosen to keep my email address private in the GitHub settings to hide my actual email address and display a no-reply email address provided by GitHub instead.

This is how the commit looks like if I do it from my local computer which uses the email address in the git config.

![Git log for commit done from local respository](/bash-git-log-1.png)

If I make a commit or change from the GitHub.com website, it hides my personal email and uses the no-reply one.

![Git log for commit done from github.com](/bash-git-log-2.png)

So we have pretty much established that it is possible to impersonate anyone using git.

# How to sign your commits

Git and GitHub allows you to sign your code using GPG. The first step is to generate a GPG key or use an existing one. The process to install and check if it is present varies depending on the operating system, so you can check the official [GitHub documentation](https://docs.github.com/en/github/authenticating-to-github/managing-commit-signature-verification/signing-commits).

You have to let Git know about the key that you have generated. The steps to configure this for each operating system is mentioned on [this page](https://docs.github.com/en/github/authenticating-to-github/managing-commit-signature-verification/telling-git-about-your-signing-key) in the GitHub Docs.

Once Git is configured and knows about the GPG key, you can sign a commit using the `-S` flag.

```
git commit -S -m "init commit"
```

Then, all you have to do is push it to the remote GitHub repo.

```
git push
```

![Verfied commit on GitHub](/verified-commit.png)

Now, your co-workers and anyone else who can view your repository can be sure that you are actually signing the commits yourself.

Please feel free to discuss in the comments, or edit this post. Thanks.
