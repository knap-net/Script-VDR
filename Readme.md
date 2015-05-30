### ~~ Script-VDR ~ Complete Installer Github Repository ~~

    This file is part of VDR Complete Installer (VCI).                   
    VCI is free software: you can redistribute it and/or modify          
    it under the terms of the GNU General Public License as published by 
    the Free Software Foundation, either version 3 of the License, or    
    (at your option) any later version.                                  
                                                                        
    VCI is distributed in the hope that it will be useful,               
    but WITHOUT ANY WARRANTY; without even the implied warranty of       
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the        
    GNU General Public License for more details.                         
                                                                        
    You should have received a copy of the GNU General Public License    
    along with VCI. see the file VCI_License.GPL, If not see             
    <http://www.gnu.org/licenses/>.                                  
                                    



    
####    Credit     

    Questo script e' stato creato per installare VDR in ambiente grafico        
    con l'aiuto di tutta la comunità vdr che conosco e tutta la loro esperienza   
    percio e' molto importante dare a loro credito          

    Ringraziamenti :                             
    a tutti gli user del sifteam forum e di vdritalia
    
    Ringraziamento Speciale :
    Klaus Schmidinger Sviluppatore VDR e Team 

    IN PARTICOLARE :                                
    Mona, unixer, fiveten_59, Grazymax, Knap, jackblow33, Alez, Shalafi, Homer314, 
    Mr Cool Span, fusibile73, ceo16, Asgarot, Armando Basile, Dadevil87 , il Mld Team e tanti ... 
    tanti altri.                              
                                                                              



####    Altre Info

    Modificato per Kubuntu 13.04 ~ 15.04   32-64 Bit      
    Modificato per Debian 7.0   32-64 Bit                                         
    Modificato per Linux Mint 15 ~ 16 Mate   32-64 Bit                            
                                                                                      
    Nuova Release Adattata per OS a 32 Bit                                                
    Compilazione Test eseguita con Vmware e Lubuntu 32 bit                                                            
                                                                                      
    Ottimizzato per CPU a 64 bit Quad Core - make -j4                                     
    Per Compilare con altre CPU Modificare il Make -jx 
    x= CPU 1 Core: make                                                                                                                          
    x= CPU 2 Core: make -j2    -    x= CPU 4 Core: make -j4                               
    x= CPU 6 Core: make -j6    -    x= CPU 8 Core: make -j8                               
    x= CPU 10 Core: make -j10  -    x= CPU 12 Core: make -j12 
    
    Configurazione Workstation:                                                                    
    Motherboard - Asus P9X79 - Chipset Intel X79                                          
    CPU - Intel Xeon E5-2658 V.2 - 2100Mhz - 8 core/16 thread -                           
    Scheda Video - NVIDIA GTX 750 Ti                                                      
    Scheda DVB-S - Skystar2 PCI   ver 2.3P                                                                                                                                     
    Driver Video - Nvidia 343.22 Installato - http://www.nvidia.it                      
                                                                                      
    Per Configurazioni diverse questo Script puo' risultare non funzionante !             
                                                                                      
    Da terminale:                                                                         
    date il comando sudo chmod 755 installer                                
    avviate lo script con il comando: sudo sh ./installer
    


  
    
####    Per usare lo script basta semplicemente

    git clone https://github.com/knap-net/Script-VDR.git
    cd Script-VDR/
    chmod +x installer && chmod 755 installer
    sudo sh ./installer
####    Per aggiornare lo script basta fare

    cd Script-VDR/
    git pull
####    Dopo l' aggiornamento si puo' lanciare lo script

    sudo sh ./installer
    
    
    
    
####    Per chi non usa la Scheda DVB-S - Skystar2 PCI ver. 2.3P

    Potrebbe creare problemi la patch con la Skystar2 HD PCIe
    Commentare con # le righe al codice cosi:
    # echo "*** 90 ***"
    # patch -p1 < 90_dvbdevice.patch; sleep 1;




####    Testato in compilazione con OS Installato e virtuale in VMware:

    ° Kubuntu 13.04 - 13.10 - 14.04 - 14.10 - 15.04 - 64 Bit
    ° Debian Wheezy 7.0 - 64 Bit
    ° Lubuntu 13.10 - 32 Bit
    ° Linux Mint 15 - 16 Maya - Mate - 32 Bit
    ° Linux Mint 16 Maya - 64 Bit





####    AGGIORNAMENTO:

    Per chi ha installato o non ha installato lo Script VDR 2.2.x precedentemente ...
    Adesso Puo' Eseguire Individualmente Upgrade o Rimozione dei Pacchetti ...






####    Per Evitare Errori in Compilazione Rimuovere

    Dalla Directory Repository Locale Precedenti Versioni di:
    vdr-patches-2.2.0
    getchannels.tar.gz





####    Plugin VDR-Manager Utilizzabile da Piattaforme Android come Client ...

    Installare sul Dispositivo Android da ... Play Store "Gestore VDR" ...
    https://play.google.com/store/apps/details?id=de.bjusystems.vdrmanager
    
    Per Utilizzare il plugin VDR-Streamdev come Server ...
    e il plugin VDR-Manager Attraverso il Client "Gestore VDR" da piattaforme Android ... avviarlo cosi:
    #> sudo ./vdr -P 'vdrmanager -p 6420 -P change' -P'streamdev-server'




####    Per Avviare Diversamente VDR in Caso di Differenze Hardware ... Provare cosi

    #> cd /usr/local/src/vdr-2.2.0
    #> sudo ./vdr -P"xineliboutput --local=sxfe --video=vaapi --audio=alsa --remote=none"
    
    Driver video da provare in Opzione "--video=xxxx" »» vaapi , vdpau . xv , xshm , ecc...






####    Per un Corretto Funzionamento Dello Script si Deve Utilizzare:

    Dal Punto 1 si passa al Punto 4 fino al Punto 17 - Schede Video Nvidia ...
    Dal Punto 1 al Punto 4 - Schede Video ATI -
    Per Chi Utilizza Le ATI Solo Test Funzionalità Con Librerie Vaapi ....
    
    Installare Driver Tramite Installer 1.0.3 - Schede Video Intel - Riavvio Del PC Al termine Installazione ...
    Download: https://01.org/linuxgraphics/downloads







####    Per Avviare VDR con Scheda Video Intel ... Provare cosi

    Eseguire Questo Comando in Shell 1
    sudo ./vdr -P"xineliboutput --local=none --remote=127.0.0.1:37890 --primary"
    
    Eseguire Questo Comando in Shell 2
    export LIBVA_DRIVER_NAME=vdpau && export LIBVA_DRIVER_NAME="i965" && export LIBVA_DRIVERS_PATH="/usr/lib/x86_64-linux-gnu/dri/" && vdr-sxfe --video=vaapi





####    Per Avviare VDR 2.2.0 Sfruttando il Supporto Vdpau Con Softhddevice, skindesigner e altri Plugin ...

    #> cd /usr/local/src/vdr-2.2.0
    #> sudo ./vdr -P'sc -B 0' -P'softhddevice' -P'osdteletext' -P'epgsearch' -P'skindesigner --logopath=/etc/vdr/logos/' -P'femon'





####    Resta Sempre Valido Quanto Scritto da "S_P" ... Per Installare Driver Intel ...

    http://forum.sifteam.eu/886359-post2.html



####    Per release datate ( Debian Based - 12.04 ) 

    si devono abilitare i repository non-free ( medibuntu )...
    Per avere tutte le dipendenze disponibili e installate dallo script.


    Si Devono Installare i Driver Proprietari - *Nvidia - *Ati -
    Per Avere Pieno Supporto Nel Plugin Softhddevice Con Libxine2 Compilato e Ottimizzato Con Vdpau e      Vaapi ...


    Molte Le Guide a Riguardo Da Seguire ...
    
