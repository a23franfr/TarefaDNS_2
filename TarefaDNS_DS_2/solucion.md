1. Tomaremos a máquina darthsidious, e configuraremola para ser servidor secundario, tanto da zona primaria de resolución directa como de resolución inversa. Captura os ficheiros de configuración en ambalas dúas máquinas. Fai unha captura onde se vexa o reinicio da máquina darthsidious, no que se vexa no log dos dous equipos e que se fixo a transferencia de zona.

    - Imaxes das configuracións das zonas.

        - Darthvader:
            
            ![imaxe1](capturas/img1.png)

        - Darthsidious:

            ![imaxe2](capturas/img2.png)

    - Reiniciamos Darthsidious:

        ![imaxe3](capturas/img3.png)

    - Logs:

        - Darthsidious:

            ![imaxe4](capturas/img4.png)

        - Darthvader:

            ![imaxe5](capturas/img5.png)

2. Engade un rexistro tipo A (Chewbacca 192.168.20.28) na zona de resolución directa e tamén na de resolución inversa.  Fai unha captura no momento do reinicio do equipo darthvader, no que se vexa o log dos dous equipos e que se amose que se fixo a transferencia de zona. Adxunta tamén unha captura do ficheiro de zona no servidor secundario.

    - Añadir Chewbacca na zona directa:

        ![imaxe6](capturas/img6.png)

    - Añadir chewbacca na zona indirecta:

        ![imaxe7](capturas/img7.png)

    - Logs:

        - Darthsidious:

            ![imaxe8](capturas/img8.png)

        - Darthvader:

            ![imaxe9](capturas/img9.png)

    - Ficheiro de zona no DNS secundario:

        ![imaxe10](capturas/img10.png)

3. Comproba que o servidor secundario pode resolver ese nome.

    ![imaxe11](capturas/img11.png)

4. Fai os cambios necesarios para que as trasferencias se fagan de forma segura empregando chaves.  Repite as capturas e vídeos do punto 2, engadindo o rexistro r2d2 (192.168.0.29)

    - Configuración da zona directa:
        
        ![imaxe12](capturas/img12.png)
    
    - Configuración da zona indirecta:

        ![imaxe13](capturas/img13.png)

    - Logs:

        - Darthvader:

            ![imaxe14](capturas/img14.png)

        - Darthsidious:

            ![imaxe15](capturas/img15.png)

    - Comprobación de r2d2 desde dns secundario:

        - Comprobación como búsqueda directa:
            
            ![imaxe16](capturas/img16.png)
        
        - Comprobación como búsqueda inversa:

            ![imaxe17](capturas/img17.png)