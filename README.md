## About Me

Hi! I'm Ayush. I'm a Linux Systems Administrator and a DevOps enthusiast.

I write my thoughts in my [microblog][1].

I've started using [SourceHut][2] as my primary git forge and [Codeberg][3] as my primary mirror.
I'll keep using GitHub as another mirror for now.

## Keys :key:

### Sign

My [OpenBSD signify][4]/[minisign][5] public key is

```
RWTOzC8OW0l2VmPS6SWB6huDGm/rX4HYdpRyFHXX9F8M18zfJUppywsB
```

I use this key to sign releases. You can also find [this key file][6] on GitHub. It's also available
as as DNS TXT record.

```
$ dig TXT signify.ayushnix.com +short | sed 's/"//g'
RWTOzC8OW0l2VmPS6SWB6huDGm/rX4HYdpRyFHXX9F8M18zfJUppywsB
```

### Encrypt

You can send me encrypted files or messages using my [age][7] public key. My email address is
available on my git commits.

```
age1dqhwu9r2wryc3j7kvpnrhg20jytts3vuzn9fyz7ku66m6tgpgfyscasmw5
```

[1]: https://microblog.ayushnix.com
[2]: https://sr.ht/~ayushnix
[3]: https://codeberg.org/ayushnix
[4]: https://github.com/aperezdc/signify
[5]: https://jedisct1.github.io/minisign/
[6]: https://raw.githubusercontent.com/ayushnix/ayushnix/master/ayushnix-signify.pub
[7]: https://github.com/FiloSottile/age
