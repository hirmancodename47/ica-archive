# ica-archive
Сайт по хитман
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Полная Энциклопедия ICA: Вселенная Hitman</title>
    <style>
        body { font-family: 'Segoe UI', Roboto, sans-serif; background-color: #0b0e14; color: #c9d1d9; margin: 0; padding: 20px; text-align: center; }
        h1 { color: #ff4545; text-transform: uppercase; letter-spacing: 2px; font-size: 2rem; margin-bottom: 5px; text-shadow: 0 0 10px rgba(255, 69, 69, 0.3); }
        .subtitle { color: #8b949e; margin-bottom: 40px; font-size: 0.9rem; text-transform: uppercase; letter-spacing: 1px; }
        .content-wrapper { max-width: 900px; margin: 0 auto; display: flex; flex-direction: column; gap: 35px; }
        
        /* Карточки разделов */
        .section-block { background: #161b22; border: 1px solid #30363d; border-top: 4px solid #ff4545; border-radius: 12px; padding: 30px; text-align: left; box-shadow: 0 15px 35px rgba(0,0,0,0.8); }
        .section-block.enemy-block { border-top-color: #ffaa00; }
        .section-block.female-block { border-top-color: #e058ff; }
        .section-block.main-hero-block { border-top-color: #ff4545; display: flex; gap: 30px; align-items: flex-start; }
        
        .section-title { font-size: 1.4rem; color: #58a6ff; border-bottom: 1px solid #30363d; padding-bottom: 6px; margin-bottom: 15px; text-transform: uppercase; font-weight: bold; letter-spacing: 0.5px; }
        .section-title.red-title { color: #ff4545; border-bottom-color: #ff4545; }
        .section-title.purple-title { color: #e058ff; border-bottom-color: #e058ff; }
        
        .bio-p { line-height: 1.7; font-size: 1.05rem; color: #e1e7ed; margin: 0 0 15px 0; }
        .bio-p:last-child { margin-bottom: 0; }
        
        /* Блок фото для Агента 47 */
        .photo-block { width: 240px; flex-shrink: 0; text-align: center; }
        .photo-block img { width: 100%; border-radius: 8px; border: 2px solid #ff4545; box-shadow: 0 8px 20px rgba(0,0,0,0.6); background-color: #0d1117; }
        .barcode-box { background: #fff; color: #000; padding: 8px; margin-top: 15px; font-family: 'Courier New', monospace; font-weight: bold; letter-spacing: 4px; border-radius: 4px; font-size: 1.1rem; text-align: center; }
        .info-block { flex: 1; }

        /* Списки и спецификации */
        .custom-list { margin: 0; padding-left: 20px; color: #e1e7ed; line-height: 1.7; }
        .custom-list li { margin-bottom: 12px; }
        .custom-list strong { color: #58a6ff; }
        .custom-list .enemy-name { color: #ffaa00; font-size: 1.1rem; text-transform: uppercase; }
        
        .bio-grid-specs { display: grid; grid-template-columns: 1fr 1fr; gap: 15px; margin-top: 20px; background: #21262d; padding: 15px; border-radius: 8px; border: 1px solid #30363d; }
        .spec-item { font-size: 0.95rem; }
        .spec-item strong { color: #ff4545; display: block; margin-bottom: 4px; text-transform: uppercase; font-size: 0.8rem; }
        
        .divider { height: 1px; background: #30363d; margin: 20px 0; }
        
        @media (max-width: 768px) {
            .section-block.main-hero-block { flex-direction: column; align-items: center; padding: 20px; }
            .photo-block { width: 100%; max-width: 240px; }
            .bio-container { flex-direction: column; align-items: center; }
            .bio-grid-specs { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <h1>АРХИВ МЕЖДУНАРОДНОГО АГЕНТСТВО КОНТРАКТОВ (ICA)</h1>
    <p class="subtitle">🔒 ВЫСШИЙ ДОСТУП: ПОЛНАЯ ГЛОБАЛЬНАЯ ЭНЦИКЛОПЕДИЯ ВСЕЙ ВСЕЛЕННОЙ HITMAN</p>

    <div class="content-wrapper">

        <!-- РАЗДЕЛ 1: ГЛАВНЫЙ ГЕРОЙ - АГЕНТ 47 -->
        <div class="section-block main-hero-block">
            <div class="photo-block">
                <img src="https://unsplash.com" alt="Агент 47">
                <div class="barcode-box">640509-040147</div>
            </div>
            <div class="info-block">
                <div class="section-title">🕵️ ЛЕГЕНДА АГЕНТСТВА: АГЕНТ 47 (ХИТМЭН)</div>
                <p class="bio-p"><strong>Происхождение:</strong> Самый результативный, скрытный и опасный наёмный убийца в мире. Он не родился естественным путём, а был создан искусственно в подземном бункере генетиком доктором Орт-Майером. Его ДНК — это смесь генов пяти жесточайших криминальных боссов планеты. Он обладает запредельной силой, абсолютным интеллектом и мгновенной реакцией.</p>
                <p class="bio-p"><strong>Почерк мастера:</strong> Занимает высший ранг в ICA. Его главная фишка — статус «Тихий убийца». 47-й способен проникнуть на любой военный или частный объект, мгновенно переодеться в одежду персонала и ликвидировать цель, замаскировав всё под несчастный случай (падение люстры, отравление, удар током), не оставив ни одной улики.</p>
                <div class="bio-grid-specs">
                    <div class="spec-item"><strong>Особые приметы</strong>Лысая голова, чёрный костюм, алый галстук</div>
                    <div class="spec-item"><strong>Фирменный арсенал</strong>Пистолеты Silverballers, струна-удавка, монетки</div>
                    <div class="spec-item"><strong>Физические данные</strong>Рост: 188 см | Вес: 85 кг</div>
                    <div class="spec-item"><strong>Текущий статус</strong>Активен. Находится на миссии</div>
                </div>
            </div>
        </div>

        <!-- РАЗДЕЛ 2: ДИАНА БЁРНВУД -->
        <div class="section-block">
            <div class="section-title">👩‍💼 Диана Бёрнвуд: Единственная связь с человечностью</div>
            <p class="bio-p"><strong>Диана Бёрнвуд (Diana Burnwood)</strong> — самый преданный и гениальный куратор Международного Агентства Контрактов (ICA). Родилась в Англии в аристократической семье. Её родители погибли из-за заговора крупных корпораций, что и привело её в ряды Агентства ради скрытого правосудия.</p>
            <p class="bio-p">Именно Диана принимала вступительный экзамен у молодого Агента 47. Она разглядела в нём уникальный потенциал и спасла от утилизации руководством. Диана стала его единственным координатором на долгие 20 лет, снабжая идеальной тактической аналитикой и оставаясь его единственным другом, удерживающим 47-го от превращения в бездушного монстра.</p>
        </div>

        <!-- РАЗДЕЛ 3: ХИТМЭНКИ (ЖЕНЩИНЫ-КИЛЛЕРЫ) -->
        <div class="section-block female-block">
            <div class="section-title purple-title">👠 Хитмэнки: Смертоносные женщины Агентства</div>
            
            <p class="bio-p"><strong>1. Виктория (Victoria) — Клон нового поколения</strong><br>
            Главная героиня игры *Hitman: Absolution*. Виктория — генетически модифицированная девочка, созданная в лабораториях ICA. По сути, она является «Хитмэнкой» нового поколения — её вывели как живое оружие, способное превзойти Агента 47. На шее она носит особый изотопный кулон, который служит источником её сверхчеловеческой силы, скорости и боевых инстинктов в бою. Диана выкрала её, чтобы спасти от участи убийцы, а Агент 47 взял под личную защиту.</p>
            
            <div class="divider"></div>
            
            <p class="bio-p"><strong>2. Отряд «Святые» (The Saints) — Элитные наёмницы</strong><br>
            Особый карательный отряд ICA, состоящий из 8 высококлассных женщин-киллеров. Их главная фишка — маскировка под католических монахинь в латексных костюмах. «Святые» безупречно владеют тактикой штурма, тяжёлым огнестрельным оружием и ракетными установками. Были посланы директором Трэвисом, чтобы ликвидировать Агента 47, но все до единой были хладнокровно уничтожены им в кукурузном поле.</p>
        </div>

        <!-- РАЗДЕЛ 4: ГЛАВНЫЕ ВРАГИ -->
        <div class="section-block enemy-block">
            <div class="section-title red-title">🎯 Сводное досье: Главные враги и цели ликвидации</div>
            <ul class="custom-list">
                <li>
                    <strong class="enemy-name">Доктор Вольфганг Орт-Майер (Wolfgang Ort-Meyer)</strong>
                    <p class="bio-p">Создатель Агента 47, вырастивший его из ДНК пяти преступных лидеров. Был ликвидирован Сорок Седьмым прямо в его подземной лаборатории в Румынии, когда 47-й поднял бунт против рабства.</p>
                </li>
                <li>
                    <strong class="enemy-name">Сергей Заворотко и Агент 17</strong>
                    <p class="bio-p">Российский мафиози и его исполнитель Агент 17 (клон-двойник 47-го). Оба были уничтожены Агентом 47 в ходе зачистки и снайперских дуэлей в Санкт-Петербурге и Сицилии.</p>
                </li>
                <li>
                    <strong class="enemy-name">Бенджамин Трэвис (Benjamin Travis)</strong>
                    <p class="bio-p">Коррумпированный директор ICA, предавший Диану и объявивший охоту на неё. Создатель отряда «Святых». Ликвидирован 47-м выстрелом в упор на кладбище.</p>
                </li>
                <li>
                    <strong class="enemy-name">Артур Эдвардс / Константа (Arthur Edwards)</strong>
                    <p class="bio-p">Глава тайного теневого правительства «Провиденс», тайно управлявшего мировой экономикой. Самый опасный противник всей современной трилогии, нейтрализованный 47-м в Карпатских горах.</p>
                </li>
            </ul>
        </div>

    </div>

</body>
</html>
