# E36-Cluster-SIMHUB
Tutorial Video AMSTUDIO YT https://youtu.be/L59NL9EuEdM 

Credit to MorGuux for Sketch Mod and Protocol
Credit to Wotever for SimHub Software


if([DataCorePlugin.GameRunning] = 1, '1', '0')
+ ';' +
format([DataCorePlugin.GameData.NewData.SpeedKmh],'0')
+ ';' + 
format([DataCorePlugin.Computed.Fuel_Percent], '0')
+ ';' +
format([DataCorePlugin.GameData.NewData.WaterTemperature], '0')
+ ';' + 
format([DataCorePlugin.GameData.NewData.Throttle], '0')

