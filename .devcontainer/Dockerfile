# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.187.0/containers/ruby/.devcontainer/base.Dockerfile
FROM mcr.microsoft.com/vscode/devcontainers/ruby:0-3.0
RUN su vscode -c "umask 0002 && . /usr/local/share/nvm/nvm.sh && nvm install 17"
RUN su vscode -c "source /usr/local/share/nvm/nvm.sh && npm install -g eslint prettier typescript"