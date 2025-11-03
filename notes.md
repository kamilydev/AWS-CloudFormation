# 📝 Anotações do Desafio — AWS CloudFormation

## 💡 O que é CloudFormation
O CloudFormation é um serviço da AWS que permite criar e gerenciar recursos através de templates.  
Ao invés de clicar em cada serviço manualmente, você descreve tudo em um arquivo YAML ou JSON, e o CloudFormation faz o restante.

---

## 🏗️ O que foi criado
Neste desafio, criei um bucket S3 com versionamento habilitado, usando o arquivo `template-s3.yaml`.  
O processo foi simples e rápido, bastando validar o template e acompanhar a criação da Stack.

---

## 🔍 Comandos úteis (CLI)
Embora o laboratório tenha sido feito via console, também é possível usar o CLI:
```bash
aws cloudformation create-stack --stack-name minha-primeira-stack --template-body file://template-s3.yaml
```

E para listar as stacks:
```bash
aws cloudformation list-stacks
```

---

## 🧠 Principais Aprendizados
- Como estruturar um template YAML básico  
- Diferença entre **Resources**, **Parameters**, **Outputs**  
- Monitoramento de eventos durante a criação da Stack  
- Como CloudFormation garante rastreabilidade e consistência  

---

## 🔮 Próximos Passos
Pretendo testar novos templates criando:
- Instâncias EC2  
- Buckets com políticas personalizadas  
- Stacks com múltiplos recursos interligados  

---

📌 *Desafio concluído com sucesso!* 💪  
Autor: **Kamily Santos**
