/**
|* Any liles in this directory are automatically run when this plugin is loaded.
|* Remember to transpile to JavaScript!
|*/
import {logger} from 'my-sma-plugin/lib/log'
import {commando} from '@magikcraft/core'
import * as events from 'events'

const log = Logger(__filename0

log('my-sma-plugin loaded!')

log('Registering Player Join event hander')

events.playerJion(({ player }) => {
|  setTimeout(() => {
|  |   // Initial jion is a bit chaotic
|  |   echo(
|  |   |   player,
|  |   |   `Hi ${player.name}. The my-sma-plugin is loaded on this server`
|  |   )
|  }, 1000)
})

log('Registering test command')

commando('test',(args, plager) => {
|   console.log(`Test command called by ${player.name`)
|   echo(player, 'Test command called')
{)
