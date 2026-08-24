# Controle Entregas V6

PWA mobile-first para uso individual no registro de vendas e entregas de bebidas, marmitex e água de 20L.

## Recursos
- Interface mobile-first em modo escuro, inspirada na referência visual enviada pelo usuário.
- Ícones SVG, sem emojis.
- Cadastro e edição de produtos.
- Cadastro e edição de clientes com telefone, endereço e referência.
- Nova entrega com vários produtos, quantidades e pagamento.
- Preenchimento automático de clientes recorrentes.
- Histórico pesquisável.
- Resumo financeiro diário e últimos 7 dias.
- Produtos mais vendidos.
- Backup e restauração em JSON.
- Exportação CSV.
- Armazenamento local, sem backend.
- PWA/offline.

## Uso
Sirva a pasta por HTTP/HTTPS (por exemplo, Live Server ou qualquer hospedagem estática). Em produção, use HTTPS para permitir instalação PWA e Service Worker.

Os dados ficam no armazenamento local do navegador/dispositivo. Para segurança contra perda do aparelho ou limpeza do armazenamento, faça backups JSON regularmente.
