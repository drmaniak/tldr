# bat

> Dosyaları yazdır ve birleştir.
> Sözdizimi vurgulama ve Git entegrasyonuna sahip bir `cat` klonu.
> Daha fazla bilgi için: <https://github.com/sharkdp/bat>.

- Bir dosyanın içeriğini standart çıktıya yazdır:

`bat {{dosya}}`

- Birkaç dosyayı hedef dosyada birleştir:

`bat {{dosya1}} {{dosya2}} > {{hedef_dosya}}`

- Birkaç dosyayı hedef dosyaya ekle:

`bat {{dosya1}} {{dosya2}} >> {{hedef_dosya}}`

- Tüm çıktı satırlarını numaralandır:

`bat {{[-n|--number]}} {{dosya}}`

- Bir JSON dosyasının sözdizimini vurgula:

`bat {{[-l|--language]}} json {{dosya.json}}`

- Desteklenen tüm dilleri görüntüle:

`bat {{[-L|--list-languages]}}`
