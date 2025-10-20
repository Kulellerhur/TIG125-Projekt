# TIG125-Projekt

https://prod.liveshare.vsengsaas.visualstudio.com/join?9A9964BF15E80EC76AE1C02F58939E172A8F

https://prod.liveshare.vsengsaas.visualstudio.com/join?E44AFF70C7ABCD1C1C861C0B104E8C6CFA26 

Hej kollegor, här kan vi samla all data och kod

k bry

Här har du Talisa: 
df.drop(["Unnamed: 0.1", "Unnamed: 0", "attencheck1", "selfadmit", "attencheck2",
         "bps_1r", "bps_2r", "bps_3r", "bps_4r", "bps_5r", "bps_6r", "bps_7r", "bps_8r",
         "moe_1r", "moe_2r", "moe_3r", "moe_4r", "moe_5r", "moe_6r", "moe_7r", 
         "moe_8r", "moe_9r", "moe_10r", "moe_11r", "moe_12r", "moe_13r", "moe_14r",
         "moe_15r", "moe_16r", "moe_17r", "moe_18r", "nfc_1r", "nfc_2r", "nfc_3r",
         "nfc_4r", "nfc_5r", "nfc_6r", "nfc_7r", "nfc_8r", "nfc_9r", "nfc_10r",
         "nfc_11r", "nfc_12r", "nfc_13r", "nfc_14r", "nfc_15r", "nfc_16r",
         "nfc_17r", "nfc_18r"], axis=1, inplace=True)

         Här har du igen din snyltare: kolumner2 = ['q1ans', 'q2ans','q3ans', 'q4ans', 'q5ans', 'q6ans', 'q7ans','q8ans', 'q9ans', 'q10ans', 'q11ans',
            'q12ans', 'q13ans','q14ans','q15ans','q16ans', 'q17ans','q18ans','q19ans','q20ans','q21ans','q22ans',
            'q23ans', 'q24ans','q25ans', 'q26ans','q27ans', 'q28ans','q29ans','q30ans','q31ans', 'q32ans','q33ans',
            'q34ans','q35ans','q36ans','q37ans','q38ans','q39ans','q40ans']
for i in kolumner2:
    df[i] = df[i].replace({"correct": 2, "incorrect": 1, " ": 0, "incorrect1": 1, "incorrect7": 1})
