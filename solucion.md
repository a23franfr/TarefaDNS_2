1. Tomaremos a máquina darthsidious, e configuraremola para ser servidor secundario, tanto da zona primaria de resolución directa como de resolución inversa. Captura os ficheiros de configuración en ambalas dúas máquinas. Fai unha captura onde se vexa o reinicio da máquina darthsidious, no que se vexa no log dos dous equipos e que se fixo a transferencia de zona.

    - Imaxes dos arquivos de configuración das zonas.

        - Darthvader:
            
            ![imaxe1.1](capturas/solapt1.1.png)

        - Darthsidious:

            ![imaxe1.2](capturas/solapt1.2.png)

    - Reinicio de Darthsidious:

        ![imaxe1.3](capturas/solapt1.3.png)

    - Logs en cada máquina:

        - Darthsidious:

            ![imaxe1.4](capturas/solapt1.4.png)

        - Darthvader:

            ![imaxe1.5](capturas/solapt1.5.png)

2. Engade un rexistro tipo A (Chewbacca 192.168.20.28) na zona de resolución directa e tamén na de resolución inversa.  Fai unha captura no momento do reinicio do equipo darthvader, no que se vexa o log dos dous equipos e que se amose que se fixo a transferencia de zona. Adxunta tamén unha captura do ficheiro de zona no servidor secundario.

    - Añadir Chewbacca en zona directa:

        ![imaxe2.1](capturas/solapt2.1.png)

    - Añadir chewbacca en zona indirecta:

        ![imaxe2.2](capturas/solapt2.2.png)

    - Logs de cada máquina:

        - Darthsidious:

            ![imaxe2.3](capturas/solapt2.3.png)

        - Darthvader:

            ![imaxe2.4](capturas/solapt2.4.png)

    - Ficheiro de zona no dns secundario:

        ![imaxe2.5](capturas/solapt2.5.png)

3. Comproba que o servidor secundario pode resolver ese nome.

    ![imaxe3.1](capturas/solapt3.1.png)

4. Fai os cambios necesarios para que as trasferencias se fagan de forma segura empregando chaves.  Repite as capturas e vídeos do punto 2, engadindo o rexistro r2d2 (192.168.0.29)

    - Configuración de la zona directa:
        
        ![imaxe4.1](capturas/solapt4.1.png)
    
    - Configuración de la zona indirecta:

        ![imaxe4.2](capturas/solapt4.2.png)

    - Logs de las máquinas:

        - Darthvader:

            ![imaxe4.3](capturas/solapt4.3.png)

        - Darthsidious:

            ![imaxe4.4](capturas/solapt4.4.png)

    - Comprobación de r2d2 desde dns secundario:

        - Comprobación como búsqueda directa:
            
            ![imaxe4.5](capturas/solapt4.5.png)
        
        - Comprobación como búsqueda inversa:

            ![imaxe4.6](capturas/solapt4.6.png)