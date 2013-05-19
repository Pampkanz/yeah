yeah
====
groups:
    Kids:
        default: true
        permissions:
        - essentials.spawn
        - essentials.rules
        - essentials.motd
        - essentials.list
        - essentials.helpop
        - essentials.help
  - essentials.pay
	- essentials.balance
	- essentials.home
	- essentials.msg
	- essentials.sethome
	- essentials.warp
	- essentials.warp.list
	- essentials.help
        - modifyworld.*
        prefix: '&7[Kid]&7'
        options:
            build: true
            rank: '1000'
    Editor:
        permissions:
        - essentials.afk
        - essentials.back
        - essentials.back.ondeath
        - essentials.balance
        - essentials.balance.others
        - essentials.balancetop
        - essentials.chat.color
        - essentials.chat.shout
        - essentials.chat.question
        - essentials.compass
        - essentials.depth
        - essentials.home
        - essentials.ignore
        - essentials.kit
        - essentials.kits.tools
        - essentials.mail
        - essentials.mail.send
        - essentials.me
        - essentials.msg
        - essentials.nick
        - essentials.pay
        - essentials.ping
        - essentials.powertool
        - essentials.protect
        - essentials.sethome
        - essentials.signs.use.*
        - essentials.signs.create.disposal
        - essentials.signs.create.mail
        - essentials.signs.create.protection
        - essentials.signs.create.trade
        - essentials.signs.break.disposal
        - essentials.signs.break.mail
        - essentials.signs.break.protection
        - essentials.signs.break.trade
        - essentials.suicide
        - essentials.time
        - essentials.tpa
        - essentials.tpaccept
        - essentials.tpahere
        - essentials.tpdeny
        - essentials.warp
        - essentials.warp.list
        - essentials.worth
        inheritance:
        - default
        prefix: '&2[Editor]&7'
        options:
            build: true
            rank: '500'
    Moderator:
        permissions:
        - essentials.ban
        - essentials.ban.notify
        - essentials.banip
        - essentials.broadcast
        - essentials.clearinventory
        - essentials.delwarp
        - essentials.eco.loan
        - essentials.ext
        - essentials.getpos
        - essentials.helpop.recieve
        - essentials.home.others
        - essentials.invsee
        - essentials.jails
        - essentials.jump
        - essentials.kick
        - essentials.kick.notify
        - essentials.kill
        - essentials.mute
        - essentials.nick.others
        - essentials.realname
        - essentials.setwarp
        - essentials.signs.create.*
        - essentials.signs.break.*
        - essentials.spawner
        - essentials.thunder
        - essentials.time
        - essentials.time.set
        - essentials.protect.alerts
        - essentials.protect.admin
        - essentials.protect.ownerinfo
        - essentials.ptime
        - essentials.ptime.others
        - essentials.togglejail
        - essentials.top
        - essentials.tp
        - essentials.tphere
        - essentials.tppos
        - essentials.tptoggle
        - essentials.unban
        - essentials.unbanip
        - essentials.weather
        - essentials.whois
        - essentials.world
        - essentials.worlds.*
        - permissions.user.promote.default
        - permissions.user.demote.default
        - permissions.manage.membership
        inheritance:
        - builder
        prefix: '&5[Moderator]&7'
        options:
            build: true
            rank: '200'
    Admin:
        permissions:
        - -essentials.backup
        - -essentials.essentials
        - -essentials.setspawn
        - -essentials.reloadall
        - essentials.*
        - permissions.manage.users
        - permissions.manage.users.permissions
        - permissions.manage.users.permissions.timed
        inheritance:
        - moderator
        prefix: '&c[Admin]&7'
        options:
            build: true
            rank: '100'
    Gods:
        permissions:
        - '*'
        inheritance:
        - admin
        prefix: '&4[God]&7'
        options:
            build: true
            rank: '0'
users:
    pampkans:
        group:
        - Admin
    heavensprotegy
        group:
	- Admin
