# phishinglinktest.com.br

### Para rodar a aplicação é necessário instalar as seguintes bibliotecas:

`pip install virtualenv`

`pip install flask`

`pip install numpy`

`pip install tensorflow`

`pip install joblib`

`pip install -U scikit-learn`

virtualenv, flask, numpy, tensorflow, joblib, scikit-learn

### Caso ocorra erros na instalação do tensorflow, abra o powershell como adminisrtador e execute:

```bash
  New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" `
-Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force
```

## Licença

[MIT](https://choosealicense.com/licenses/mit/)


## Autores

- [@AleFelipe](https://github.com/AleFeliphe)
- [@tiagorfm](https://github.com/tiagorfmohr)
