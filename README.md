Esta es una prueba de SISTEMA OPERATIVO KALI LINUX
EN DONDE ENCONTRAMOD UN ERROR DE CARGA DE BIBLIOTECAS DE PYTHON BIBLIOTECA "PYINSTALADOR 
AQUI LES MUESTRO COMO SOLUCIONE EL ERROR VOLVIENDO EJECUTABLE EL JUEGO DE LA VIBORITA 
DEJO UN LINK A LOS ARCHIVOS RESTANTES DENTRO DE UN DRIVE PARA QUE PUEDAN EJECUTARLO DE MANERA CORRECTA YA QUE GITHUB NO ME PERMITE ALMACENAR MAS DE 100 ARCHIVOS
EJECUTA ESTOS COMANDOS 
 nano ~/.zshrc
ESTO NOS PERMITIRA MODIFICAR NUESTRO CAMINO DE KALI LINUX Y PODER ANADIR LA BIBLIOTECA DE FORMA MANUAL SI NO TE DIVERS ESE PRUEBA CON 
 nano ~/.bashrc
A VECES SUELO HABER DIFERENCIAS EN VERSIONES DE KALI LINUX, LARGO PROCEDIMIENTOS A MODIFICAR LA LÍNEA DEL CAMINO 
 exportar PATH="$HOME/.local/bin:$PATH"
MODIFICA INICIO POR LA RUTA DE TU ESCRITURA DE PITÓN 
LUEGO GUARDAMOS Y CERRAMOS SIGUIENTE A ESO EJECUTAMOS EL SOURCE 
 fuente ~/.zshrc
 fuente ~/.bashrc
LUEGO DE HACER TODOS ESTOS PASOS DEBEMOS MODIFICAR NUESTRO ARCHIVO .ESPECIFICACIONES DE PYINSTALLER POR 
                
     un análisis =(['juego_viborita.py'],
     pathex=['/ruta/a/tu/script'],
     binarios=[],
     datos=[],
     importaciones ocultas=[],
     hookspath=[],
     runtime_hooks=[],
     excluye=[],
     win_no_prefer_redirects=False,
     win_private_assemblies=False,
     cifrado=block_cifrado,
     noarchive=False)
     pyz = PYZ(a.pure, a.zipped_data,
     cifrado=block_cifrado)
     exe = EXE(pyz,
     a.guiones,
     [],
    excluir_binarios=True,
    nombre='juego_viborita',
     debug=False,
     bootloader_ignore_signals=False,
     strip=False,
     upx=Verdadero,
     runtime_tmpdir=None,
     console=True,
    desactivar_windowed_traceback=False,
     objetivo_arch=Ninguno,
     codesign_identity=None,
     derechos_file=None)
     coll = RECOLECTAR(exe,
     a.binarios,
     a.zipfiles,
     a.datas,
     strip=False,
     upx=Verdadero,
     upx_exclude=[],
    nombre='juego_viborita')
MODIFICAR TODO LO RELACIONADO A "JUEGO_VIBORITA" POR EL GOBIERNO QUE DESEA TRANSFORMAR EN EJECUTABLE 
enlace de viborita: https://drive.google.com/drive/folders/1JHfdw-ScQi3HL6balrTj-n5WKsFkc4m9?usp=sharing
