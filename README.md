# Lista-de-Tarefas

tarefas = []

def adicionar_tarefa(tarefa):
    tarefas.append(tarefa)
    print("Tarefa adicionada com sucesso!")

def mostrar_tarefas():
    print("Lista de Tarefas:")
    for index, tarefa in enumerate(tarefas, start=1):
        print(f"{index}. {tarefa}")

adicionar_tarefa("Lavar o carro")
adicionar_tarefa("Fazer compras")
mostrar_tarefas()
