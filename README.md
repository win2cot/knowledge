# WindowsPCだけど極力LinuxベースでClaude開発
## Setup
### WSLでUbuntu環境作成
- Distribution `Ubuntu-24.04` を作成。詳細省略
- ユーザのパスワードを忘れた・・・
  - PowerShellから以下でリセット
    ```
    PS C:\Users\ishik> wsl -u root -d Ubuntu-24.04
    ```
    ```
    root@pavilion:/mnt/c/Users/ishik# passwd win2cot
    ```
### Github CLI導入
- https://github.com/cli/cli/blob/trunk/docs/install_linux.md#debian
- `repo clone` とか適当に済ます
