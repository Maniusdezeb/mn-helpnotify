[mn-hulpnotify]


icons zijn te vinden op: https://fontawesome.com/v5.15/icons?d=gallery&p=2

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

exports: 

Open: 
    exports["mn-helpnotify"]:OpenNotify({
        icon = "fas fa-university",
        text = "[E] Open Bank",
        color = "#B33F40"
    })
Close : 
    exports["mn-helpnotify"]:CloseNotify()




----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Code Voorbeeld Single marker:


Citizen.CreateThread(function()
    while true do 
        Wait(0)
        local coords, ped = GetEntityCoords(GetPlayerPed(-1)), GetPlayerPed(-1)
        local dist = GetDistanceBetweenCoords(coords, 414.6677, -989.6602, 29.41808, true)

        if dist < 10 then 
            DrawMarker(20,414.6677, -989.6602, 29.41808 - 0.2, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.5, 0.3, 0.2, 147,112,219, 100, false, true, 2, true, nil, nil, false)
            if dist < 1.5 then 
                exports["mn-helpnotify"]:OpenNotify({
                    icon = "fas fa-university",
                    text = "[E] Open Bank",
                    color = "#B33F40"
                })
                if IsControlJustReleased(0, 38) then 
                    print("Je hebt op E gedrukt")
                end
            else
                exports["mn-helpnotify"]:CloseNotify()
            end
        end
    end
end)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Code Meerdere markers (for loop) 

Citizen.CreateThread(function()
    while true do 
        while Playerjob == nil do Wait(500) end
        Wait(0)
        local ped = GetPlayerPed(-1)
        local coords = GetEntityCoords(ped)
        local sleep = true
        while Playerjob == nil do Wait(500) end
        for k,v in pairs(MN.Markers) do 
            local dist = GetDistanceBetweenCoords(coords, v.x, v.y, v.z, true)
            if dist < 10 then
                slapen = false
                DrawMarker(20,v.x, v.y, v.z - 0.2, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.5, 0.3, 0.2, 65,105,225, 100, false, true, 2, true, nil, nil, false)
                CloseNotify = true  
                if dist < 2 then 
                    CloseNotify = false                            
                        exports["mn-helpnotify"]:OpenNotify({
                        icon = v.icon,
                        text = v.text,
                        color = v.color
    })
                    if IsControlJustReleased(0, 38) then 
                        -- bla bla
                    end
                end
            end
        end
        if CloseNotify then 
            exports["mn-helpnotify"]:CloseNotify()
        end
        if slapen then 
            Wait(500)
        end
    end
end)



made by mn#0810 Founder of MN SCRIPTS