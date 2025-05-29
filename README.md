# 🚲 EntreBicis

**EntreBicis** és una aplicació mòbil desenvolupada per fomentar la mobilitat sostenible mitjançant l’ús de la bicicleta. L’aplicació permet registrar els quilòmetres recorreguts pels usuaris i convertir-los en punts bescanviables per recompenses en establiments i associacions locals.

A més, inclou funcionalitats de verificació de rutes per garantir que els recorreguts es realitzen realment en bicicleta, així com un sistema de gestió de recompenses administrat per l’organització. L’aplicació també ofereix geolocalització per traçar rutes i facilitar la navegació.

El projecte està desenvolupat amb un backend en Java i un frontend en Kotlin amb Jetpack Compose, seguint els estàndards moderns de desenvolupament per a aplicacions mòbils.

<br><br>
## 📱 Funcionalitats principals

- **Registre de rutes amb GPS**: Els usuaris poden iniciar i finalitzar rutes, que s’enregistren automàticament.
- **Validació de rutes**: Un administrador valida les rutes perquè es transformin en punts de saldo.
- **Conversió de quilòmetres a punts**: Cada km recorregut equival a 1 punt. Els punts poden ser fraccionaris.
- **Sistema de recompenses**:
  - Crear recompenses (nom i ubicació).
  - Reservar i recollir recompenses.
  - Visualitzar detall de les recompenses assignades.
- **Gestió de saldo**: Els punts s’acumulen i es poden gastar en recompenses.
- **Gestió d'usuaris**: Registre, modificació de dades i login/logout.
- **Mapa interactiu**: Visualització de les rutes en un mapa amb zoom i consulta de punts.
- **Frontend Android en català**: Interfície moderna i atractiva, seguint Material Design.

<br><br>
## 🧑‍💻 Tecnologies utilitzades

### Backend
- **Java**
- **Spring Boot** amb arquitectura RESTful
- **Maven**
- **Autenticació amb hash** de contrasenyes
- **Docker** per al desplegament

### Frontend (Mobile)
- **Kotlin**
- **Jetpack Compose**
- **Arquitectura MVVM + Clean Architecture**
- **State management amb StateFlow**
- **Material Design**
- **Navegació amb components moderns**

<br><br>
## 🖼️ Captures de pantalla

### Vista general de l'app

<table>
  <tr>
    <td align="center">
      <img src="screenshots/Login.PNG" width="200"/><br>
      <sub>Login</sub>
    </td>
    <td align="center">
      <img src="screenshots/RecuperarContraseña.PNG" width="200"/><br>
      <sub>Recuperar contrasenya</sub>
    </td>
    <td align="center">
      <img src="screenshots/ElMeuPerfil.PNG" width="200"/><br>
      <sub>El meu perfil</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="screenshots/EditarPerfil.PNG" width="200"/><br>
      <sub>Editar perfil</sub>
    </td>
    <td align="center">
      <img src="screenshots/LesMevesRutes.PNG" width="200"/><br>
      <sub>Les meves rutes</sub>
    </td>
    <td align="center">
      <img src="screenshots/RutaIniciada.PNG" width="200"/><br>
      <sub>Ruta iniciada</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="screenshots/LesMevesReserves.PNG" width="200"/><br>
      <sub>Les meves reserves</sub>
    </td>
    <td align="center">
      <img src="screenshots/Recompenses.PNG" width="200"/><br>
      <sub>Recompenses</sub>
    </td>
    <td align="center">
      <img src="screenshots/DetallRecompensa.PNG" width="200"/><br>
      <sub>Detall recompensa</sub>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="screenshots/ReservarRecompensa.PNG" width="200"/><br>
      <sub>Reservar recompensa</sub>
    </td>
    <td align="center">
      <img src="screenshots/PuntDeBescanvi.PNG" width="200"/><br>
      <sub>Punt de bescanvi</sub>
    </td>
    <td align="center">
      <img src="screenshots/DetallsPuntBescanvi.PNG" width="200"/><br>
      <sub>Detalls punt de bescanvi</sub>
    </td>
  </tr>
</table>

> 📸 Aquestes captures són de l'app real en funcionament.


<br><br>
## 🎥 Vídeo de demostració

📺 [Veure vídeo de presentació (en català)](https://drive.google.com/file/d/12OXJbUOP_mFEEN2-G7enPdad6RWxxcwq/view?usp=sharing)

<br><br>
## 📄 Codi Font i Documentació (Repositori Privat)

- **[Codi font i Documentació](https://gitlab.com/ylopez7/entrebicis)**

---

> Aquest projecte ha estat desenvolupat de manera **individual** en el marc del cicle formatiu de Desenvolupament d'Aplicacions Multiplataforma (DAM) - curs 2024-2025.
