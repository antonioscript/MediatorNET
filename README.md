# MediatorNET
Repository exemplifying the isolated use of the mediator pattern

---

## Mediator
Mediator funcionando como uma forma de desacomplar as informações entre os serviços:

</br>![image](https://github.com/user-attachments/assets/53e8cafc-e05d-4f1d-b43a-a95137486534)

</br></br>Supondo que o serviço 1 precisa se comunicar com o serviço 6, é esse processo que acontece internamente:
</br></br>![image](https://github.com/user-attachments/assets/0e0df32a-5aaf-4469-9fb4-aa012fc7edb6)

</br></br>Simplificando novamente o processo:
- Request
- Handler
- Response

</br></br>![image](https://github.com/user-attachments/assets/26ba8712-7662-4c12-acbf-69f1e7a7a3f0)

## CQRS
O padrão CQRS geralmente está sempre ligado ao padrão Mediator:

</br></br>![image](https://github.com/user-attachments/assets/f944b5f5-1d51-4753-8c16-5dc17a8b953a)

</br>Exemplo caso não fosse utilizado o CQRS:

</br>![image](https://github.com/user-attachments/assets/6dcc2bb0-8610-4d99-92ba-04ff5d3e531a)

</br> Exemplo usando o CQRS:

</br></br>![image](https://github.com/user-attachments/assets/d5eabbc0-4625-4d1f-9831-f53443370174)


## Referência
https://www.youtube.com/watch?v=sUjNZAYTZwI

https://www.youtube.com/watch?v=BewUyKLZjtc
