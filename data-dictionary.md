owners.json {
    <owner id>: {
        'abbv': <team name abbreviation>,
        'owner': <owner name>,
        'team': <team name>,
        
        'weekly_rosters': {
            '0': {<drafted player id> : <season point total>},
            
            <week number (1-13)> : {
                'lineup': {<active player id> : <points scored>},
                'bench': {<bench player id> : <points scored>}
            }
        }
    }
}
 

players.json {
    <player id>: {
        'name': <player name>, 
        'position': <player position abbreviation>, 
        'team': <NFL team abbreviation>
    },
}


schedules.json {
    <owner id>: {<week number (1-13)>: <opponent id>}
}




