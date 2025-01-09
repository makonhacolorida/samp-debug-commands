# SA:MP 0.3.7 R5
> Eu tinha upado esse mesmo repositorio em uma outra conta minha do github chamada "theselvmord", então fiquem despreocupados hduashusadh </br>

> Aviso: Aconselho usar Auto-Inject pois a verificação do Modo Debug acontece desde do DllMain do propio SA:MP.

---
> [!CAUTION]
> Esses comandos serão liberados através de um ByPass, ou seja "método utilizado por jogadores para contornar restrições ou sistemas de detecção de cheats", não me responsabilizo por nenhuma merda que você vai fazer com isso, deixei os avisos e as documentações tanto do codigo quanto dos meus testes em base dos comandos, obviamente você pode ter o risco de ser banido de algum servidor se ficar usando que nem um louco. Espero que consigam fazer algo mais divertido com esses codigos!
---

# 
![a](https://github.com/tisiohw/samp-bypass-debug/blob/main/code_ida.png)

- Documentação das Funções
  - `dword_1026DFE8` -> Valor a ser Burlado, Meio que é a variavel que indica se você está no Debug Mode ou Não.
  - `sub_10069770`   -> Pelo oque eu vi, ele define qual função tal comando pre definido irá executar, Por Ex: o "/quit" vai executar a função: sub_100689E0
  - `unk_100E6300`   -> Por mais que seja um valor desconhecido, creio que seja o "/v" pois usa a mesma função do "/vehicle".

- Documentação do Funcionamento das Funções
  - `/vsel` -> Pelo oque eu vi, Meio que funciona como um Ghost Hack pois quando você entra no carro aparentemente você só volta ser sicronizado com o servidor apos sair do veiculo, assim resultando em um possivel chamado de Teleport pelo AntiCheat.
  - `/set_weather` // `/player_skin` -> Funcionando Perfeitamente
  - `/set_time` -> Na maioria dos Servidores a sicronização com o tempo do servidor e o seu meio que entra em conflito

# Comandos que poderão ser usados:
- /vsel
- /vehicle
- /player_skin
- /set_weather
- /set_time
