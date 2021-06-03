---
title: Bash Condition
weight: 210
menu:
  notes:
    name: Condition
    identifier: notes-bash-condition
    parent: notes-bash
    weight: 10
---


<!-- Condition -->
{{< note title="ファイルの存在判定" >}}

- ファイルが存在する場合に実行
    ```bash
    if [ -e ${file} ];then
        echo hello, world
    fi
    ```
<br> 

- ファイルが存在しない場合に実行
    ```
    if [ ! -e ${file} ]; then
        echo hello, world
    fi
    ```
    `!`を条件の先頭につける
{{< /note >}}
