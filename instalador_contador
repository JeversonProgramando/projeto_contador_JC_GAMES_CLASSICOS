#!/bin/bash
#Créditos 
#Jogos tirados de uma imagem do baocera.linux v5.26 by "Parceiros de emulação" 
#Escrito por Jeverson Dias Da Silva & CauãBatista Dias Da Siva ( @JCGAMESCLASSICOS )
#JOGOS TIRADOS DE UMA IMAGEM DE 8 GIGAS BAIXADA DO SITE "PARCEIROS DA EMULAÇÃO"
#PORTANTO OS DEVIDOS CRÉDITOS A ELES TAMBEM, E O NOSSO MUITO OBRIGADO! 



yad --center --title="BOT COLEÇÕES  JC GAMES CLÁSSICOS" --text="Estamos escrevendo no sistema, porém todas as mudanças poderão ser revertidas caso não fique satisfeito com os resultados!" --image=/usr/share/icons/Adwaita/256x256/devices/input-gaming.png --button="OK":0
#Partiu rodar o update!!!

#====================================================================================================================================================================================================
#====================================================================================================================================================================================================
LINK=/userdata/system/Desktop/download_automatico/download_sistema_13_g.txt

/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh -system internet -rom $LINK &

mkdir /usr/share/MyControl


tar -xvf CONTADOR.tar

mv /userdata/downloads/CONTADOR/"CONTADOR GERAL" /userdata/
mv 	/userdata/downloads/CONTADOR/contabilidade /userdata/ 
mv CONTADOR /usr/share/MyControl/ 
rm /userdata/downloads/CONTADOR.tar




touch "CONTADOR_GERAL.desktop" /userdata/downloads

echo "[Desktop Entry]" >> /userdata/downloads/CONTADOR++

echo "Version=1.0" >> /userdata/downloads

echo "Icon=/usr/share/MyControl/CONTADOR/contador/capas/contador.png" >> /userdata/downloads/CONTADOR++

echo "Exec=/usr/share/MyControl/CONTADOR/contador/CONTADOR.sh" >> /userdata/downloads/CONTADOR++

echo "Terminal=false" >> /userdata/downloads/CONTADOR++

echo "Type=Application" >> /userdata/downloads/CONTADOR++

echo "Categories=desenvolvimento;" >> /userdata/downloads/CONTADOR++

echo "Name=CONTADOR_GERAL" >> /userdata/downloads/CONTADOR++

echo "GenericName=COINS" >> /userdata/downloads/CONTADOR++

echo "Comment=Adição ou exclusão de sistemas" >> /userdata/downloads/CONTADOR++

echo "Keywords=CONTABILIDADE" >> /userdata/downloads/CONTADOR++

echo "NoDisplay=false" >> /userdata/downloads/CONTADOR++

rm CONTADOR_GERAL.desktop








#mv /userdata/system/configs/emulationstation/es_systems.cfg /userdata/system/configs/emulationstation/es_systems.cfg.BKP
cp /usr/share/emulationstation/es_systems.cfg /userdata/system/configs/emulationstation/es_systems.cfg
sleep 1



#===================================================================================================================================================================================================
#===================================================================================================================================================================================================



sed -i '$d' /userdata/system/configs/emulationstation/es_systems.cfg

echo " <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>CONTADOR DE CRÉDITOS</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>CONTADOR</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Linux Fundation</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>2023</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>software</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/usr/share/MyControl/CONTADOR/contador/</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.sh .SH</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/bin/sh %ROM% %CONTROLLERSCONFIG%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>LINUX</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>contador</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <group></group>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg




#===================================================================================================================================================================================================
#===================================================================================================================================================================================================
echo "<!--Artfury Adicionado Por  @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg


echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Artfury</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>artfury</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/artfury</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>artfury</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg









#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--Btmups Adicionado Por @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg



echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Btmups</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>btmups</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/btmups</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>btmups</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg









#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--The King Of Fighters Adicionado Por @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg



echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>The king of fighters</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>kof</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/kof</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>kof</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg









#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--Mortal Kombat Adicionado por @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg




echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Mortal Kombat</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>mk</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/mk</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>mk</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg








#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--Metal Slug Adicionado Por @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg




echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Metal Slug</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>mslug</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/mslug</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>mslug</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg









#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--Samurai Shodown Adicionado Por @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg




echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Samuray shodown</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>samurai</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/samurai</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>samurai</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg









#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--Shmups Adicionado Por @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg




echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Shmups</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>shmups</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/shmups</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>shmups</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg









#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--Street Fighters Adicionado Por @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg




echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Street Fighters</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>street</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/street</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>street</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg









#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--World Wheroes Adicionado Por @JCGAMESCLASSICOS-->"  >> /userdata/system/configs/emulationstation/es_systems.cfg




echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>World Heroes</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>wheroes</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Final Burn</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>None</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/fbneo/wheroes</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.fba .FBA .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>wheroes</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">fbneo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps1</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps2</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_cps3</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>fbalpha2012_neogeo</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg







#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "<!--Desligar o sistema e Reiniciar o sistema Adicionado Por @JCGAMESCLASSICOS-->" >> /userdata/system/configs/emulationstation/es_systems.cfg



echo "<system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Desligao o sistema</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>exit</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>software</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/desligar</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.sh .SH</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.sh .SH</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/bin/sh %ROM% %CONTROLLERSCONFIG%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>desligar</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg









#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 




echo "<!--Kodi Midia Player Adicionado Por @JCGAMESCLASSICOS-->" >> /userdata/system/configs/emulationstation/es_systems.cfg


echo "<system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Kodi</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>kodi</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>software</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/kodi</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.sh .SH</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.sh .SH</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/bin/sh %ROM% %CONTROLLERSCONFIG%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>kodi</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg
        







#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 




echo "<!--Futebol Adicionado Por @JCGAMESCLASSICOS-->" >> /userdata/system/configs/emulationstation/es_systems.cfg


echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Futebol</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>futebol</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Nintendo</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>1990</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>console</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/snes/futebol</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.smc .SMC .bin .BIN .bs .BS .fig .FIG .sfc .SFC .gd3 .GD3 .gd7 .GD7 .dx2 .DX2 .bsx .BSX .swc .SWC .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>snes</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>futebol</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>bsnes</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>bsnes_hd</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mesen-s</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">snes9x</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>snes9x_next</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>catsfc</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg













#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 




echo "<!--Super Mario Adicionado Por @JCGAMESCLASSICOS-->" >> /userdata/system/configs/emulationstation/es_systems.cfg


echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Super Mario</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>mario</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Nintendo</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>1990</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>console</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/snes/mario</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.smc .SMC .bin .BIN .bs .BS .fig .FIG .sfc .SFC .gd3 .GD3 .gd7 .GD7 .dx2 .DX2 .bsx .BSX .swc .SWC .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>snes</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>mario</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>bsnes</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>bsnes_hd</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mesen-s</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">snes9x</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>snes9x_next</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>catsfc</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg










#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 




echo "<!--Mario Hacks Por @JCGAMESCLASSICOS-->" >> /userdata/system/configs/emulationstation/es_systems.cfg


echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Mario Hacks</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>mario_hacks</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Nintendo</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>1990</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>console</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/snes/mario_hacks</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.smc .SMC .bin .BIN .bs .BS .fig .FIG .sfc .SFC .gd3 .GD3 .gd7 .GD7 .dx2 .DX2 .bsx .BSX .swc .SWC .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>snes</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>mario_hacks</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>bsnes</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>bsnes_hd</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mesen-s</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">snes9x</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>snes9x_next</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>catsfc</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg












#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 




echo "<!--Racing Adicionado Por @JCGAMESCLASSICOS-->" >> /userdata/system/configs/emulationstation/es_systems.cfg


echo "  <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Racing</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>racing</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Nintendo</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>1990</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>console</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/snes/racing</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.smc .SMC .bin .BIN .bs .BS .fig .FIG .sfc .SFC .gd3 .GD3 .gd7 .GD7 .dx2 .DX2 .bsx .BSX .swc .SWC .zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>snes</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>racing</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>bsnes</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>bsnes_hd</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mesen-s</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">snes9x</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>snes9x_next</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>catsfc</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg










#===================================================================================================================================================================================================
#===================================================================================================================================================================================================


echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 




echo "<!--Mame Hacks Por @JCGAMESCLASSICOS-->" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo " <system>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <fullname>Mame Hacks</fullname>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <name>hacks</name>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <manufacturer>Mame</manufacturer>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <release>1972</release>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <hardware>arcade</hardware>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <path>/userdata/roms/mame/hacks</path>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <extension>.zip .ZIP .7z .7Z</extension>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <command>/usr/lib/python2.7/site-packages/configgen/emulatorlauncher.sh %CONTROLLERSCONFIG% -system %SYSTEM% -rom %ROM%</command>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <platform>arcade</platform>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <theme>hacks</theme>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        <emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            <emulator name=\"libretro\">" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                <cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mame</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core default=\"true\">mame0200</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mame0174</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mame0160</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mame0139</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mame078plus</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                    <core>mame037</core>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "                </cores>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "            </emulator>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "        </emulators>" >> /userdata/system/configs/emulationstation/es_systems.cfg

echo "  </system>" >> /userdata/system/configs/emulationstation/es_systems.cfg


echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 
echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 
echo "" >> /userdata/system/configs/emulationstation/es_systems.cfg 





echo "</systemList>" >> /userdata/system/configs/emulationstation/es_systems.cfg

