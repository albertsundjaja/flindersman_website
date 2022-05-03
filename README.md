# Flindersman website

This is the code base for my personal website https://flindersman.com

## Requirements

To deploy to AWS S3, edit the `config.toml` with your S3 configuration

Get authenticated with `AWS CLI` and run the command

```
env HUGO_ENV="production" hugo

hugo deploy
```