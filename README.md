# LIBCOLOR_EVELIN
colores
Paso 1. Agregue el repositorio JitPack a su archivo de compilaci

Agréguelo en su raíz build.gradle al final de los repositorios:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Paso 2. Agregar la dependencia

	dependencies {
	        implementation 'com.github.EvelinHancco:LIBCOLOR_EVELIN:-SNAPSHOT'
	}
