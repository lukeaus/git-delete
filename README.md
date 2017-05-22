# git-delete

## Introduction

Ever git sick of deleting local and and remote branches one at a time?

Delete multiple local and remote branches that begin with the same string.

## Code Samples

Replace these

    git push origin --delete foo/bug-1
    git branch --delete foo/bug-1

    git push origin --delete foo/bug-2
    git branch --delete foo/bug-2

    git push origin --delete foo/feature-1
    git branch --delete foo/feature-1

    git push origin --delete foo/feature-2
    git branch --delete foo/feature-2
    ...


With this

    git-delete foo/


## Installation

Download git-delete and put it somewhere on your $PATH.

Make it executable

    chmod +x git-delete
