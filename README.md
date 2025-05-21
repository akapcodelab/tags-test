# Тест запрета на пуш тегов в репу организации

9

## Текущие запреты:
v1.87.*

v1.88.????.0

## Демонстрация эффекта
```
git push --tags --force
...
To https://github.com/akapcodelab/tags-test.git
 * [new tag]         1.88.0123.0 -> 1.88.0123.0
 * [new tag]         1.88.1234.0 -> 1.88.1234.0
 * [new tag]         1.88.12345.0 -> 1.88.12345.0
 * [new tag]         1.88.12346.0 -> 1.88.12346.0
 * [new tag]         v1.88.1.0 -> v1.88.1.0
 * [new tag]         v1.88.11.0 -> v1.88.11.0
 * [new tag]         v1.88.11000.0 -> v1.88.11000.0
 * [new tag]         v1.88.115.0 -> v1.88.115.0
 * [new tag]         v1.88.55324.0 -> v1.88.55324.0
 ! [remote rejected] v1.87.40757.0 -> v1.87.40757.0 (push declined due to repository rule violations)
 ! [remote rejected] v1.88.0123.0 -> v1.88.0123.0 (push declined due to repository rule violations)
 ! [remote rejected] v1.88.1123.0 -> v1.88.1123.0 (push declined due to repository rule violations)
 ! [remote rejected] v1.88.1124.0 -> v1.88.1124.0 (push declined due to repository rule violations)
 ! [remote rejected] v1.88.1155.0 -> v1.88.1155.0 (push declined due to repository rule violations)
 ! [remote rejected] v1.88.1156.0 -> v1.88.1156.0 (push declined due to repository rule violations)
 ! [remote rejected] v1.88.1324.0 -> v1.88.1324.0 (push declined due to repository rule violations)
error: failed to push some refs to 'https://github.com/akapcodelab/tags-test.git'
```

## Настройки гитхаба:
![image](https://github.com/user-attachments/assets/006c6db4-c61e-44b1-9768-46b9ee3b9012)
![image](https://github.com/user-attachments/assets/16ed6720-8c0b-44ac-ab57-26df3b35d9e8)
