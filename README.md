# Visual Studio Code

VS Code Configurations

Extensions: 
- Intelephense
- TALL stack
- vscode-icons or Material Icon Theme

# WSL - Windows Subsystem Linux

Follow the instructions

https://medium.com/@habbema/desvendando-o-wsl-2-no-windows-11-c7649545026d

https://github.com/codeedu/wsl2-docker-quickstart?tab=readme-ov-file#integra%C3%A7%C3%A3o-com-vscode

# Docker / Sail

Alter "git clone" a project
```
docker run --rm \
    -u "$(id -u):$(id -g)" \
    -v "$(pwd):/var/www/html" \
    -w /var/www/html \
    laravelsail/php82-composer:latest \
    composer install --ignore-platform-reqs
```
Reference: https://laravel.com/docs/9.x/sail#installing-composer-dependencies-for-existing-projects

- docker system prune - Delete not used containers and image


# Terminal

https://dev.to/henriquemsimoes/instalando-e-configurando-zsh-e-oh-my-zsh-4bem
