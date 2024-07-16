# Nubit# Nubit

> There will be different developments in Nubit in the coming days

> For now, we are just setting up a node.

> We connect with our wallet [here](https://alpha.nubit.org/)

> We enter these commands to any server:

`screen -S nubit`
`curl -sL1 https://nubit.sh | bash`

> We save the keys between our logs.
> After saving, we exit the screen with ctrl a+d.

![image](https://github.com/ruesandora/Nubit/assets/101149671/2ef4e7cd-7d50-42e7-9864-23f20399bb17)

> We verify the pubkey after 15 minutes, we get our total score of 6k.

<img width="622" alt="Screenshot 2024-06-24 17 22 44" src="https://github.com/ruesandora/Nubit/assets/101149671/f81d1cf5-139a-413c-a830-ef00b42c0339">

##

- If the screen went too fast, to see your pubkey (try outside the screen)

```sh
$HOME/nubit-node/bin/nkey list --p2p.network nubit-alphatestnet-1 --node.type light
```

> **key: Enter the part that says on the site.
The part that says address: is your nubit address.**

##

- To see the recovery phrases (mnemonics) of your address:

```sh
nano $HOME/nubit-node/mnemonics.txt
```
