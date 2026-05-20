# tb_tow


Description

tb_tow_sale_point is a lightweight QBCore script that lets tow truck drivers earn money by delivering towed vehicles to designated sale locations around the map. Simply hook up a vehicle, drive to a sale point, and press E to sell it for a random cash or bank payout.

Features

Multiple configurable sale locations with map blips and ground markers
Job restriction — only allowed jobs (e.g. tow) can see sale points and sell vehicles
Configurable allowed tow vehicle models (flatbed, towtruck, towtruck2, etc.)
Random payout within a min/max price range
Payout to either cash or bank (configurable)
Blip and marker fully customizable (sprite, color, scale, size, type)
Clean, easy-to-read config.lua — no escrow on config
Requirements

QBCore Framework
Installation

Drop tb_tow_sale_point into your resources folder
Add ensure tb_tow_sale_point to your server.cfg
Configure config.lua to your liking
Configuration Preview

Config.AllowedJobs = { "tow" }

Config.SaleLocations = {
    vector3(407.89, -1635.18, 29.29), -- city
    vector3(1766.05, 3787.43, 33.84), -- sandy
    vector3(59.43, 6517.34, 31.46),   -- LS Docks
}

Config.MinPrice = 500
Config.MaxPrice = 1500
Config.PayoutType = "cash" -- or "bank"
