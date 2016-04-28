## Rev. 5.6.5
- Sistemato bug plugin skindesigner
- Rieseguire il Punto 1, A, Creazione, Repository Locale


## Rev. 5.6.4
- Modifica Repository Sifinstallrepo ~ Nuove Funzioni rimozione pacchetti obsoleti
- Nuovo Menù Punto [1] Repository Sifinstallrepo
- Aggiornato Librerie Libva 1.7.0
- Aggiornato Librerie Libva-intel-driver 1.7.0
- Modifica Menù Punto [2] - Aggiunto Note
- Modifica Menù Punto [3] - LIBVPX - FFMPEG ~ Versione Selezionabile ~ Stabile o Testing



## Rev. 5.6.3
- Update && Revision By Fiveten_59



## Rev. 5.6.2
- Aggiunto Supporto NVIDIA Video Codec 6.1 SDK - hardware encode(NVENC) and hardware decode(NVCUVID)
- Per Ulteriori Dettagli NVENC consultare -> https://developer.nvidia.com/nvidia-video-codec-sdk
- Aggiornato FFmpeg da Git repository a Release Stable 2.8.6 Snapshot
- Aggiunto Supporto in FFmpeg 2.8.6 con Vdpau e NVENC (H.264 - H.265)
- Aggiornato Librerie Libvpx 1.5.0
- Aggiunte nuove patch con il plugin softhddevice
- Aggiunto in apt-get install dipendenze mancanti
- Rieseguire il Punto 1, A, Creazione, Repository Locale



## Rev. 5.6.1
- Aggiunto Supporto Librerie LIBVDPAU 1.1.1 - Non Supportate piu' ufficialmente dai driver nvidia.
- Aggiunto Supporto Librerie VDPAUINFO 1.0 - Tools Utilità Informazioni Generali
- Rimosso Limitazione GetChannels 0.7.2 in Creazione Settings ed Allineato Versioni
- Eliminati Altri Bug minori
- Rieseguire il Punto 1, A, Creazione, Repository Locale



## Rev. 5.6.0
- Aggiornati alcuni plugin e inseriti altri tre nuovi
- Installazione Kodi modificata (ora possibilità di caricare le tre possibili versioni: stabile - release - sviluppo)
- Aggiornati alcuni loghi
- Eliminati Altri Bug minori
- Rieseguire il Punto 1, A, Creazione, Repository Locale



## Rev. 5.5.9
- Aggiunto e Implementato Nuovo Metodo GetChannels 0.7.2 In Creazione Lista Canali
- Satelliti Disponibili: Da 4.8E a 30.0W - Crea Parametri, Caid e Pid Audio/Video
- Versione Pubblica Con Limitazione - Crea Circa 130~135 Canali Per Satellite - Dimostrativa
- Effettuare Piu' Selezioni Dei Satelliti ... Per Avere Diversi Settings Nello Stesso channels.conf
- Crea Settings Ordinati Per Frequenza Crescente - Non Ordinati per Tipologia o Categoria
- Rimosso Sezione Lamedb2vdr.sh - Getchannels - Conversione e Aggiornamento
- Aggiunto Nuove Fuonzionalità - Editor Grafici Lista Canali per Personalizzazione && Modifica
- Sezione Editor - Cle4vdr_0.5.3 ~ ChannelEditor_1.9.2.1 
- Editor Disponibili in Ambiente Grafico Qt e Gtk2 per Architettura x86 & x86_64
- Aggiornato Librerie Libdrm 2.4.67
- Aggiornato Librerie LIBVA 1.6.2
- Aggiornato Librerie LIBVA-INTEL-DRIVER 1.6.2
- Eliminati Altri Bug minori
- Rieseguire il Punto 1, A, Creazione, Repository Locale



## Rev. 5.5.8
- Modificate ... alcune parti rese compatibili con Ubuntu 15.10 e verosimilmente con la prossima versione LST 16.04
- Rimane vdr in versione Stabile 2.2.0 
- Sistemato un paio di bug



## Rev. 5.5.7
- Modifica del Menu' Principale Script creati nuovi "Submenu" con diversa numerazione 
- Creati Nuovi Sottomenu per selezionare i vari pacchetti con Installa/Rimuovi - Aggiunto Relative Note
- Aggiornato Librerie Libdrm 2.4.65
- Aggiornato Librerie LIBVA 1.6.1
- Aggiunto Supporto Librerie LIBVA-INTEL-DRIVER 1.6.1
- Aggiunto Supporto Librerie LIBVA-VDPAU-DRIVER 0.7.4 + Aggiunto Patch per corretta compilazione
- Aggiornato repository di x265 con HG Videolan
- Aggiornato ffmpeg con release stable 2.8
- Eliminare dalla cartella Repository Locale i pacchetti Obsoleti o Aggiornati
- Rieseguire il Punto 1,A - Download & Update Repository Locale
- Eliminato un bug in compilazione xine-lib 1.2.6 - Errore di Libtool



## Rev. 5.5.6
- Inserite alcune traduzioni in italiano di plugin e skin
- Eliminare dalla sifinstallrepo traduzioni.tar.gz e ricaricarle con il Punto 1a
- Eliminato un bug librerie libva



## Rev. 5.5.5
- Aggiornato Librerie Libdrm versione 2.4.64
- Aggiornato Librerie Libva versione 1.6.0
- Aggiornato il menù e modifiche minori applicate al codice per adattamento nuova release
- Rieseguire il Punto 1a - Download & Update Repository Locale



## Rev. 5.5.4
- Eliminare e ricaricare con punto 1-a dalla sifinstallrepo i plugin skindesigner - flatplus - softhddevice
- Caricati altri plugin a livello sperimentale (Epg-daemon in particolare) dove segnalato utilizzabili dalle  prossime versioni
- I plugin flatplus skindegner tvguideng e weatherforecast hanno ora traduzioni in italiano
- Eliminato dai plugin caricati in default menuorg e reelchannellist (spostati al punto 14)
- Altri minori bug



## Rev. 5.5.3
- Caricati due plugin a livello sperimentale (Setup e Mpv) utilizzabili dalle prossime versioni.
- Caricabile tramite script ulteriori skin di skindesigner non gestibili direttamente dal plugin.
- Eliminare dalla sifinstallrepo - vdrsymbols
- Effettuare il Punto 1 - [a] Creazione - Download locale repository nuovi plugins



## Rev. 5.5.2
- Spostata sezione w_scan ed eliminato versione originaria di getchannels ora implementata dalla Rev. 5.5.1
Caricati due plugin a livello sperimentale (Setup e Mpv) utilizzabili dalle prossime versioni



## Rev. 5.5.1
- Implementazione Codice Al Punto 17 Integrazione **Script Lamedb2vdrgetchannel.sh** (Autore daredavil87)
- **Mod. By Grazymax** - Converte Setting Enigma2 in File "nome;provider" usati in Getchannel {Beta Test}
- Modifica Skin Script Menu' & Creazione Sub-menu Getchannel Selezione settings Vhannibal - Morpheus
- Nuovo metodo implementato scarica/converte/aggiorna dati kingofsat compresi Pid Audio/Video - 13.0E Okay
- Aggiornato x265 - checkinstall --pkgversion="*" - Compatibilita' in Ubuntu 15.04 Repo Update
- Aggiornato Libreie x264 da Git "Compila da release Stable" - Aggiornato checkinstall --pkgversion="*"
- Aggiornato ffmpeg - checkinstall --pkgversion="*" - Compatibilita' in Ubuntu 15.04 Repo Update
- Altre modifiche minori applicate



## Rev. 5.5.0
- Eliminare dalla sifinstallrepo - vdrsymbols - setup16 - setup43 - vdr-plugin-skindesigner
- Effettuare il Punto 1 - [a] Creazione - Download locale repository nuovi plugins
- Modifica al codice per aggiornamento e modifiche del git vdr-plugin-skindesigner 0.5.1
- Rimossi temi di default aggiunti a vdr-plugin-skindesigner
- Avviare VDR con opzione: 
- -P'skindesigner -l /etc/vdr/logos/ -i /usr/share/vdr/plugins/skindesigner/skins/'
- Per caricare le skin si va in Menu/Opzioni/Plugins/Skindesigner "install new skin"
- Dopo l' installazione si cambia il tema sempre in Menu/Opzioni/OSD
- Aggiunto vdr-plugin-play da git
- Altre modifiche minori applicate



## Rev. 5.4.9
- Modifica codice aggiornamento Skindesigner e tema glasslike



## Rev. 5.4.8
- Implementazione Codice Al Punto 17 Integrazione Script Lamedb2vdr.sh (Autore daredavil87) - Converte Setting Enigma2
- Modifica Skin Script Menu' & Creazione Sub-menu per Selezionare settings Vhannibal - Morpheus
- Settare in VDR dal menu "F1" / "Opzioni" / "Scheda DVB" / Aggiornamento canali / "Solo Pid" 
- Setting E2 convertiti dallo Script Lamedb2vdr.sh al primo utilizzo richiedono un attesa di 10~60 Secondi
- Alcuni canali al primo utilizzo richiedono un attesa di 3~4 minuti per autoaggiornarsi i Pid Audio/Video



## Rev. 5.4.7
- Aggiornamento by fiveteen_59 vari plugins e patch - cecremote - play - mp3
- Rimossa la skin tryout e aggiunto skin glassylike
- Aggiunto Externalplayer nei plugin di default
- Rimosso l' appswitcher
- Modifica punto 20 adattato con interfaccia dialog
- Altre modifiche minori applicate



## Rev. 5.4.6
- Aggiunto Plugin by fiveteen_59 - mp3 - play - externalplayer
- Effettuare il Punto 1 - [A] Creazione - Download locale repository nuovi plugins
- Aggiunto al Punto 14 selezione dei plugins - per usarli in vdr (-P'mp3' -P'play' -P'externalplayer')



## Rev. 5.4.5
- Modifiche al codice e risoluzione di alcuni errori
- Altre modifiche minori al codice.



## Rev. 5.4.4
- Revisione codice per errore in compilazione libdrm
- Update Minor Fix



## Rev. 5.4.3
- Aggiornato Librerie Libdrm versione 2.4.61
- Aggiornato Librerie Libvpx versione 1.4.0
- Modifica al codice per adattamento nuova release
- Rieseguire il Punto 1 - Download & Update Repository Locale



## Rev. 5.4.2
- Aggiunto al Punto 6 Librerie X265 HEVC Encoder - ** Premere Q per eseguire compilazione ** -
- Aggiunto Sottomenu in FFmpeg selezione configurazione con supporto X265
- Modifica Skin Menu' Script per adattamento nuova release



## Rev. 5.4.1
- Allineamento Ultima Release fiveten_59 con Release 5.4 - Update release da 5.4 a 5.4.1
- Aggiunte librerie di supporto compilazione e Test Fisico in Linux Mint 16 Mate
- Da segnalare l'installazione manuale {libjansson-dev - libiso9660-dev - Other} non presenti
- Da segnalare che non si trova presente Kodi in Linux Mint 16 Mate
- Applicate Notificazioni Errori e divergenze in Github Segnalate
- Rinominato Script e Sorgenti 
- Altre modifiche applicate



## Rev. 5.4
- Modifica e Aggiornamento del Plugin IPTV - Configurazione e Test Funzionalita' - By Fiveten_59
- Adattamento Release V.5.3 al nuovo Mod.
- Aggiornamento Librerie Libdrm - Libva - successive release
- Altre modifiche minori 


## Rev. 5.3 
- Modifica dei Menu nella skin dello script - integrazione con 'Dialog'.
- Modifica al codice di Kodi per una corretta esecuzione.
- Modifica del codice e dei sotto menu - separatori interni.
- Altre modifiche minori al codice.



## Rev. 5.2 
- Aggiornato al punto 17 codice Kodi
- Aggiunto al Punto 17 codice rimozione Kodi
- Modifica alla Skin del menù di selezione.
- Modifica al Codice per adattarlo alla nuova Release.



## Rev. 5.1 
- Aggiunto al Punto 13 Plugin Vdr-manager & Test Funzionalità
- Aggiunto al Punto 13 Plugin Vdr-streamdev & Test Funzionalità
- Modifica al logo di Tux e Upgrade Progressivo.
- Modifica al Codice per adattarlo alla nuova Release.



## Rev. 5.0 
- Aggiornato Getchannel (Autore Armando Basile) - Vers. 0.7.0 - Download 13.0E - Crea Settings da Kingofsat
- Aggiornato Patch VDR 2.2.0 - Patch - dvbdevice.c - Modifica Segnale & Qualità (Skystar 2 dvb-s pci rev.2.3)
- Aggiunto VDR-Plugin-SC - GIT - al Punto 13 & 15 - Utile a molti Utenti ;D
- Aggiornato Librerie - LIBDRM 2.4.60
- Aggiornato Librerie - LIBVA 1.5.1
- Modifica al Codice per adattarlo alla nuova Release.
