# qb-tunerjob

made by DrLuckyRp

Edited version of qb-mechanicjob

go to qb-bossmenu and add to config 
['tuner'] = vector3(150.87, -3013.5, 7.04)

now go to qb-core/shaird/jobs.lua and add 

    ['tuner'] = {
		label = 'Turner',
		defaultDuty = true,
		offDutyPay = false,
		grades = {
            ['0'] = {
                name = 'Recruit',
                payment = 50
            },
			['1'] = {
                name = 'Novice',
                payment = 75
            },
			['2'] = {
                name = 'Experienced',
                payment = 100
            },
			['3'] = {
                name = 'Advanced',
                payment = 125
            },
			['4'] = {
                name = 'Manager',
				isboss = true,
                payment = 150
            },
        },
	},
