# Police Garage with target

Add this to qb-target

    local peds = {
        `ig_trafficwarden`,
    }
    AddTargetModel(peds, {
        options = {
            {
                event = "garage:menu",
                icon = "fas fa-car",
                label = "Police Garage",
            },
        },
        distance = 2.5
    })



Preview:
https://streamable.com/jdwcle

**Requirements**

qb-Target
qb-menu
