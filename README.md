run in SQL:

INSERT INTO bbvehicles (citizenid,plate,model) SELECT citizenid,plate,vehicle FROM player_vehicles

UPDATE `bbvehicles` SET `stats`='{"damage":10,"fuel":98}' WHERE stats is NULL

UPDATE `bbvehicles` SET `props`='{}' WHERE props? is NULL

UPDATE `bbvehicles` SET `state`='impound' WHERE state = 'unknown' or state is NULL

UPDATE `bbvehicles` SET `parking` = '' WHERE parking is NULL
