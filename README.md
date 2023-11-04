# Proxy em container realizando redirecionamentos para outras instancias
Exemplo simples do funcionamento de um proxy reverso Nginx em Container Docker, que realiza redirecionamentos para serviços que estão em outras instâncias. Alcançabilidade dos serviços ao proxy deve ser suprida pela rede interna.

Para bom funcionamento é necessário um DNS estático configurado, redirecionando as urls para o IP da instância que roda o docker daemon.
