# Dicionário com um exemplo de usuário e senha
usuarios = {
    "usuario1": "senha123",
    "usuario2": "senha456"
}

# Função para verificar o login
def verificar_login(usuario, senha):
    if usuario in usuarios and usuarios[usuario] == senha:
        return True
    else:
        return False

# Loop principal
while True:
    print("Sistema de Login")
    print("----------------")
    
    # Solicitando as credenciais ao usuário
    usuario_input = input("Nome de usuário: ")
    senha_input = input("Senha: ")
    
    # Verificando as credenciais
    if verificar_login(usuario_input, senha_input):
        print(f"\nBem-vindo, {usuario_input}!\n")
        break
    else:
        print("\nNome de usuário ou senha incorretos. Tente novamente.\n")
