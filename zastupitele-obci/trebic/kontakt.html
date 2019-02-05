---
layout: blank-article
description: 
keywords: 
title: Kontaktuj nás
---

<?php
    mb_internal_encoding("UTF-8");
    $hlaska = '';
    if (isset($_GET['uspech']))
        $hlaska = 'Email byl úspěšně odeslán, brzy vám odpovíme.';
    if ($_POST) // V poli _POST něco je, odeslal se formulář
    {
        if (isset($_POST['jmeno']) && $_POST['jmeno'] &&
            isset($_POST['email']) && $_POST['email'] &&
            isset($_POST['zprava']) && $_POST['zprava'] &&
            isset($_POST['rok']) && $_POST['rok'] == date('Y'))
        {
            $hlavicka = 'From:' . $_POST['email'];
            $hlavicka .= "\nMIME-Version: 1.0\n";
            $hlavicka .= "Content-Type: text/html; charset=\"utf-8\"\n";
            $adresa = 'roman.pasek@pirati.cz';
            $predmet = 'email z pirátského webu';
            $uspech = mb_send_mail($adresa, $predmet, $_POST['zprava'], $hlavicka);
            if ($uspech)
            {
                $hlaska = 'Email byl úspěšně odeslán, brzy vám odpovíme.';
                header('Location: index.php?uspech=ano#kontakt');
                exit;
            }
            else
                $hlaska = 'Email se nepodařilo odeslat. Zkontrolujte adresu.';
        }
        else 
            $hlaska = 'Formulář není správně vyplněný!';
    }
?>
