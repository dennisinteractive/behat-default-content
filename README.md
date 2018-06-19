# Behat Default Content
Automatically populates content

### Installation
1. `composer require dennisdigital/behat-default-content:dev-master`

You might need to add it to repositories first
```
"repositories": {
    "behat-default-content": {
      "type": "vcs",
      "url": "git@github.com:dennisinteractive/behat-default-content.git",
      "no-api": true
    }
.
.
.
```

2. Edit behat.yml and add the contexts and configuration following the example in [behat.yml.dist]: https://github.com/dennisinteractive/behat-default-content/blob/master/behat.yml.dist

### Running
- Go into the tests folder
- Run `./behat --format=pretty`
