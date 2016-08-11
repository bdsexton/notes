# Git Commands

**Commonly Used Git Commands**

## Configuration

### Basic Setup

First things first! Let's check our global identification settings.

```shell
git config --global user.name
```

```shell
git config --global user.email
```

Look good? Great! Nothing there or want to change what is? Easy!

```shell
git config --global user.name "Firsty Lastington"
```

```shell
git config --global user.email username@example.com
```

### Text Editor Configuration

Sometimes Git opens a text editor for you to enter some text, but it may not be the text editor you prefer. You can specify your own like so:

```shell
git config --global core.editor atom
```

## Reference

[Git - First-Time Git Setup](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)

[Setting your username in Git - User Documentation](https://help.github.com/articles/setting-your-username-in-git/)

[Setting your email in Git - User Documentation](https://help.github.com/articles/setting-your-email-in-git/)

## Who compiled this info?

This information was gathered and prepared by [Brian Sexton](http://briansexton.com/) of [Carroket, Inc.](http://carroket.com/)