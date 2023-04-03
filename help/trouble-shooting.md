---
title: Felsöka kontrollpanelen
description: Lär dig hur du felsöker Kontrollpanelen.
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
source-git-commit: 1b1efe35c2ddcf379d1e847064ffa8be18d276b3
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 100%

---

# Felsöka [!UICONTROL Control Panel]

## Inloggning och hemsida

### Symptom: Det går inte att logga in på Experience Cloud

**Gör så här:**
Användaren måste hitta sitt IMS-organisations-ID (xxx). Administratören måste lägga till användaren i produktprofilen &quot;Campaign-xxx-Admins&quot; för varje instans som denne vill hantera. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som användare.

### Symptom: Länkar i Experience Cloud Home för åtkomst till [!UICONTROL Control Panel] visas inte för en användare

**Orsak:**
Användare ser inte länkarna förrän de läggs till som användare i produktprofilen _Campaign-xxx-Administrators/Admin_.

**Gör så här:**
Administratören måste lägga till användaren i Product Profile _Campaign-xxx-Admins_ för varje instans som de ska hantera. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som användare.

### Symptom: En instans visas inte i [!UICONTROL Control Panel]

**Orsak:**
Sannolikt måste användaren läggas till som *användare* Produktprofil _Campaign-xxx-Administrators/Admin_ för instansen som saknas

**Gör så här:**
Administratören måste lägga till användaren i Produktprofil _Campaign-xxx-Admins_  för varje instans som ska hanteras. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som &quot;användare&quot;.

### Användbara videor

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=0n)

*Kontrollera ett IMS-organisations-ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=0n)

*Så lägger du till en administratör i produktprofilen administratörer för att kunna använda [!UICONTROL Control panel] (01:03 min)*

### Användbar dokumentation

* [Lär känna kontrollpanelen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=sv)
* [Hantera behörigheter i [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=sv)

## Upprätta en anslutning till en SFTP-server (klient eller API)

För anslutning till SFTP-servrar krävs:

* [!UICONTROL Allow listing]-IP-adressen som används för anslutning till SFTP-servern
* Ett privat/offentligt nyckelpar som måste registreras i Adobe Campaign
* Om du ansluter till SFTP-servern direkt behöver du även en SFTP-klientprogramvara

### Användbar dokumentation {#helpful-docs}

* [Logga in på SFTP-servern](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=sv)
