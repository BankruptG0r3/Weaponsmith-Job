# Weaponsmith-Job
Weaponsmith Job for RSG Framework

originaly from RexshackGaming full credit goes too them

reworked the progress bar too use ox_lib to stop the errors

Dependancies:

rsg-core,
ox_lib

Installation:
ensure that the dependancies are added and started
add the following table to your database : rsg-weaponsmith.sql
add rsg-weaponsmith to your resources folde

Add this too shared jobs:

    ['valweaponsmith'] = { --valentine
        label = 'Valentine Weaponsmith',
        defaultDuty = true,
        offDutyPay = false,
        grades = {
            ['0'] = { name = 'Trainee', payment = 25 },
            ['1'] = { name = 'Master', isboss = true, payment = 75 },
        },
    },
    ['rhoweaponsmith'] = { -- rhodes
        label = 'Rhodes Weaponsmith',
        defaultDuty = true,
        offDutyPay = false,
        grades = {
            ['0'] = { name = 'Trainee', payment = 25 },
            ['1'] = { name = 'Master', isboss = true, payment = 75 },
        },
    },

Commands
/inspect (used to inspect a held weapon)


