---
title: Lägga till SSL-certifikat
description: Läs mer om hur du lägger till SSL-certifikat för att skydda dina underdomäner.
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 98%

---

# Lägga till SSL-certifikat

Med [!UICONTROL Control Panel] i Adobe Campaign kan du lägga till SSL-certifikat för att skydda underdomänerna.

## Komma åt hantering av underdomäner på kontrollpanelen

För att få åtkomst till hantering av underdomäner på kontrollpanelen ska du gå du till:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Solution picker: **[!DNL Campaign]** > kortet **[!UICONTROL Control Panel]** > kortet **[!UICONTROL Subdomains & Certificates]**

  eller
* Direkt från webbadressen: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Stegvis lägga till SSL-certifikat

Att lägga till SSL-certifikat kräver tre steg:

### 1. Skapa en begäran om certifikatsignering

Begäran om certifikatsignering (CSR) krävs för köp av ett SSL-certifikat. Den måste genereras för instansen och underdomänerna du planerar att säkra.

I videon nedan förklaras hur du skapar en begäran om certifikatsignering på kontrollpanelen.

>[!VIDEO](https://video.tv.adobe.com/v/31317?learn=on){trancript=true}

*Skapa en begäran om certifikatsignering (02:36 min)*

>[!NOTE]
>
>Flera förbättringar har gjorts i CSR-genereringsprocessen:
>
>* När du genererar en CSR kan du nu välja en av de inkluderade underdomänerna som Gemensamt namn.
>* Nu kan du kopiera CSR-sammanfattningen innan du genererar CSR.
>* När en CSR har skapats kan du hämta den igen från jobbloggarna. Den här funktionen gäller inte certifikat som genererats före den här versionen.
>
>![Hämta CSR](/help/assets/download-csr.gif)
>
>Se [produktdokumentationen](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=sv) om du vill veta mer.
>

### 2. Köpa SSL-certifikat

Efter att ha erhållit CSR måste du köpa SSL-certifikatet från en certifikatutfärdare som godkänts av din organisation.

### 3. Installera SSL-certifikat

När du har erhållit SSL-certifikatet måste det installeras för de underdomäner du planerar att säkra.

I videon nedan förklaras hur du installerar SSL-certifikat i [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?learn=on){trancript=true}

*Installera SSL-certifikat (01:25 min)*


