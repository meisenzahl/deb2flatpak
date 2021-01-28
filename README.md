<div align="center">
  <span align="center">
    <img width="80" height="80" class="center" src="https://raw.githubusercontent.com/elementary/icons/master/mimes/128/application-vnd.debian.binary-package.svg" alt="deb">
    <img width="80" height="80" class="center" src="https://raw.githubusercontent.com/elementary/icons/master/actions/48/go-next.svg" alt="convert">
    <img width="80" height="80" class="center" src="https://raw.githubusercontent.com/elementary/icons/master/mimes/128/application-vnd.flatpak.ref.svg" alt="flatpak">
  </span>
  <h1 align="center">deb2flatpak</h1>
  <h3 align="center">Tool to help migrate Debian packages to Flatpak</h3>
</div>

## Setup

It is recommended to use a virtual Python environment. Create one as follows:

```
$ python -m venv env
```

Activate it and install the dependencies:

```
$ source env/bin/activate
(env) $ pip install -r requirements.txt
```

If you want to use the environment, you must activate it:

```
$ source env/bin/activate
(env) $
```

## elementary AppCenter

For testing, all apps of [elementary AppCenter](https://appcenter.elementary.io/) are built.


[![com.github.aggalex.contacts](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.aggalex.contacts/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.aggalex.contacts)<br>
[![com.github.aggalex.wineglass](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.aggalex.wineglass/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.aggalex.wineglass)<br>
[![com.github.aimproxy.cyfrif](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.aimproxy.cyfrif/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.aimproxy.cyfrif)<br>
[![com.github.aimproxy.dotfonts](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.aimproxy.dotfonts/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.aimproxy.dotfonts)<br>
[![com.github.akiraux.akira](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.akiraux.akira/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.akiraux.akira)<br>
[![com.github.alainm23.byte](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.alainm23.byte/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.alainm23.byte)<br>
[![com.github.alainm23.ioncolorgenerator](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.alainm23.ioncolorgenerator/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.alainm23.ioncolorgenerator)<br>
[![com.github.alainm23.planner](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.alainm23.planner/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.alainm23.planner)<br>
[![com.github.alcadica.develop](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.alcadica.develop/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.alcadica.develop)<br>
[![com.github.alcinnz.odysseus](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.alcinnz.odysseus/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.alcinnz.odysseus)<br>
[![com.github.alecaddd.sequeler](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.alecaddd.sequeler/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.alecaddd.sequeler)<br>
[![com.github.alecaddd.taxi](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.alecaddd.taxi/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.alecaddd.taxi)<br>
[![com.github.aleksandar-stefanovic.urmsimulator](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.aleksandar-stefanovic.urmsimulator/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.aleksandar-stefanovic.urmsimulator)<br>
[![com.github.allen-b1.news](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.allen-b1.news/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.allen-b1.news)<br>
[![com.github.alonsoenrique.quotes](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.alonsoenrique.quotes/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.alonsoenrique.quotes)<br>
[![com.github.arshubham.cipher](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.arshubham.cipher/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.arshubham.cipher)<br>
[![com.github.arshubham.gitignore](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.arshubham.gitignore/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.arshubham.gitignore)<br>
[![com.github.artemanufrij.findfileconflicts](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.findfileconflicts/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.findfileconflicts)<br>
[![com.github.artemanufrij.graphui](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.graphui/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.graphui)<br>
[![com.github.artemanufrij.hashit](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.hashit/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.hashit)<br>
[![com.github.artemanufrij.imageburner](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.imageburner/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.imageburner)<br>
[![com.github.artemanufrij.metronome](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.metronome/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.metronome)<br>
[![com.github.artemanufrij.playmymusic](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.playmymusic/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.playmymusic)<br>
[![com.github.artemanufrij.playmyvideos](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.playmyvideos/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.playmyvideos)<br>
[![com.github.artemanufrij.regextester](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.regextester/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.regextester)<br>
[![com.github.artemanufrij.screencast](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.screencast/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.screencast)<br>
[![com.github.artemanufrij.showmypictures](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.showmypictures/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.showmypictures)<br>
[![com.github.artemanufrij.translit](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.translit/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.translit)<br>
[![com.github.artemanufrij.webpin](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.artemanufrij.webpin/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.artemanufrij.webpin)<br>
[![com.github.babluboy.bookworm](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.babluboy.bookworm/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.babluboy.bookworm)<br>
[![com.github.babluboy.nutty](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.babluboy.nutty/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.babluboy.nutty)<br>
[![com.github.bartzaalberg.alias](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.alias/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.alias)<br>
[![com.github.bartzaalberg.bookmark-manager](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.bookmark-manager/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.bookmark-manager)<br>
[![com.github.bartzaalberg.lottery](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.lottery/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.lottery)<br>
[![com.github.bartzaalberg.php-tester](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.php-tester/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.php-tester)<br>
[![com.github.bartzaalberg.python-tester](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.python-tester/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.python-tester)<br>
[![com.github.bartzaalberg.recipes](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.recipes/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.recipes)<br>
[![com.github.bartzaalberg.snaptastic](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.snaptastic/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.snaptastic)<br>
[![com.github.bartzaalberg.sudokular](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.sudokular/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.sudokular)<br>
[![com.github.bartzaalberg.vala-tester](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bartzaalberg.vala-tester/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bartzaalberg.vala-tester)<br>
[![com.github.basjam.valacompiler](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.basjam.valacompiler/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.basjam.valacompiler)<br>
[![com.github.bbuhler.hostsmanager](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bbuhler.hostsmanager/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bbuhler.hostsmanager)<br>
[![com.github.bcedu.museic](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bcedu.museic/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bcedu.museic)<br>
[![com.github.bcedu.shutdownscheduler](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bcedu.shutdownscheduler/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bcedu.shutdownscheduler)<br>
[![com.github.bcedu.valasimplehttpserver](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bcedu.valasimplehttpserver/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bcedu.valasimplehttpserver)<br>
[![com.github.bcedu.vgrive](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bcedu.vgrive/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bcedu.vgrive)<br>
[![com.github.bernardodsanderson.vido](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bernardodsanderson.vido/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bernardodsanderson.vido)<br>
[![com.github.bharatkalluri.gifup](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bharatkalluri.gifup/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bharatkalluri.gifup)<br>
[![com.github.bleakgrey.tootle](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bleakgrey.tootle/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bleakgrey.tootle)<br>
[![com.github.brendanperry.stocks](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.brendanperry.stocks/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.brendanperry.stocks)<br>
[![com.github.bytepixie.snippetpixie](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.bytepixie.snippetpixie/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.bytepixie.snippetpixie)<br>
[![com.github.calo001.fondo](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.calo001.fondo/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.calo001.fondo)<br>
[![com.github.calo001.luna](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.calo001.luna/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.calo001.luna)<br>
[![com.github.cassidyjames.clairvoyant](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cassidyjames.clairvoyant/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cassidyjames.clairvoyant)<br>
[![com.github.cassidyjames.dippi](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cassidyjames.dippi/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cassidyjames.dippi)<br>
[![com.github.cassidyjames.ephemeral](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cassidyjames.ephemeral/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cassidyjames.ephemeral)<br>
[![com.github.cassidyjames.ideogram](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cassidyjames.ideogram/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cassidyjames.ideogram)<br>
[![com.github.cassidyjames.palette](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cassidyjames.palette/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cassidyjames.palette)<br>
[![com.github.cassidyjames.principles](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cassidyjames.principles/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cassidyjames.principles)<br>
[![com.github.chasinglogic.tardis](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.chasinglogic.tardis/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.chasinglogic.tardis)<br>
[![com.github.christophernugent.locksmith](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.christophernugent.locksmith/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.christophernugent.locksmith)<br>
[![com.github.cjfloss.envelope](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cjfloss.envelope/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cjfloss.envelope)<br>
[![com.github.cleac.olifant](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cleac.olifant/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cleac.olifant)<br>
[![com.github.cryptowyrm.copypastegrab](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.cryptowyrm.copypastegrab/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.cryptowyrm.copypastegrab)<br>
[![com.github.dahenson.agenda](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.dahenson.agenda/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.dahenson.agenda)<br>
[![com.github.danrabbit.harvey](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.danrabbit.harvey/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.danrabbit.harvey)<br>
[![com.github.danrabbit.lookbook](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.danrabbit.lookbook/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.danrabbit.lookbook)<br>
[![com.github.danrabbit.nimbus](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.danrabbit.nimbus/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.danrabbit.nimbus)<br>
[![com.github.davidmhewitt.clipped](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.davidmhewitt.clipped/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.davidmhewitt.clipped)<br>
[![com.github.davidmhewitt.torrential](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.davidmhewitt.torrential/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.davidmhewitt.torrential)<br>
[![com.github.dbhowell.peeq](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.dbhowell.peeq/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.dbhowell.peeq)<br>
[![com.github.dcharles525.crypt](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.dcharles525.crypt/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.dcharles525.crypt)<br>
[![com.github.dcharles525.pho](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.dcharles525.pho/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.dcharles525.pho)<br>
[![com.github.devalien.workspaces](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.devalien.workspaces/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.devalien.workspaces)<br>
[![com.github.djaler.formatter](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.djaler.formatter/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.djaler.formatter)<br>
[![com.github.donadigo.appeditor](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.donadigo.appeditor/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.donadigo.appeditor)<br>
[![com.github.donadigo.eddy](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.donadigo.eddy/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.donadigo.eddy)<br>
[![com.github.dr-styki.screenrec](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.dr-styki.screenrec/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.dr-styki.screenrec)<br>
[![com.github.efdos.mupengui](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.efdos.mupengui/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.efdos.mupengui)<br>
[![com.github.elfenware.badger](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.elfenware.badger/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.elfenware.badger)<br>
[![com.github.eudaldgr.elements](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.eudaldgr.elements/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.eudaldgr.elements)<br>
[![com.github.fleury08.prettifier](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.fleury08.prettifier/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.fleury08.prettifier)<br>
[![com.github.geigi.cozy](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.geigi.cozy/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.geigi.cozy)<br>
[![com.github.gijsgoudzwaard.image-optimizer](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.gijsgoudzwaard.image-optimizer/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.gijsgoudzwaard.image-optimizer)<br>
[![com.github.hannesschulze.optimizer](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.hannesschulze.optimizer/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.hannesschulze.optimizer)<br>
[![com.github.hezral.inspektor](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.hezral.inspektor/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.hezral.inspektor)<br>
[![com.github.jeremypw.gnonograms](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.jeremypw.gnonograms/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.jeremypw.gnonograms)<br>
[![com.github.jeremyvaartjes.comgen](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.jeremyvaartjes.comgen/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.jeremyvaartjes.comgen)<br>
[![com.github.jeremyvaartjes.ping](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.jeremyvaartjes.ping/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.jeremyvaartjes.ping)<br>
[![com.github.jeremyvaartjes.subminder](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.jeremyvaartjes.subminder/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.jeremyvaartjes.subminder)<br>
[![com.github.jmoerman.go-for-it](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.jmoerman.go-for-it/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.jmoerman.go-for-it)<br>
[![com.github.juarezfranco.tarefas-desktop](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.juarezfranco.tarefas-desktop/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.juarezfranco.tarefas-desktop)<br>
[![com.github.kmal-kenneth.monilet](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.kmal-kenneth.monilet/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.kmal-kenneth.monilet)<br>
[![com.github.lainsce.aesop](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.aesop/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.aesop)<br>
[![com.github.lainsce.beemy](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.beemy/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.beemy)<br>
[![com.github.lainsce.coin](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.coin/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.coin)<br>
[![com.github.lainsce.dot-matrix](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.dot-matrix/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.dot-matrix)<br>
[![com.github.lainsce.khronos](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.khronos/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.khronos)<br>
[![com.github.lainsce.niu](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.niu/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.niu)<br>
[![com.github.lainsce.notejot](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.notejot/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.notejot)<br>
[![com.github.lainsce.palaura](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.palaura/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.palaura)<br>
[![com.github.lainsce.quilter](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.quilter/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.quilter)<br>
[![com.github.lainsce.rakugaki](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.rakugaki/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.rakugaki)<br>
[![com.github.lainsce.reganam](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.reganam/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.reganam)<br>
[![com.github.lainsce.timetable](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.timetable/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.timetable)<br>
[![com.github.lainsce.yishu](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.lainsce.yishu/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.lainsce.yishu)<br>
[![com.github.linuxhubit.catfacts](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.linuxhubit.catfacts/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.linuxhubit.catfacts)<br>
[![com.github.linuxhubit.gitscover](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.linuxhubit.gitscover/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.linuxhubit.gitscover)<br>
[![com.github.linuxhubsubpixel.license](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.linuxhubsubpixel.license/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.linuxhubsubpixel.license)<br>
[![com.github.louis77.tuner](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.louis77.tuner/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.louis77.tuner)<br>
[![com.github.ma1onso.quotes](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.ma1onso.quotes/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.ma1onso.quotes)<br>
[![com.github.manexim.home](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.manexim.home/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.manexim.home)<br>
[![com.github.manexim.news](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.manexim.news/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.manexim.news)<br>
[![com.github.manexim.typewriter](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.manexim.typewriter/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.manexim.typewriter)<br>
[![com.github.marbetschar.time-limit](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.marbetschar.time-limit/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.marbetschar.time-limit)<br>
[![com.github.matfantinel.moneta](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.matfantinel.moneta/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.matfantinel.moneta)<br>
[![com.github.matfantinel.reminduck](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.matfantinel.reminduck/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.matfantinel.reminduck)<br>
[![com.github.mdh34.hackup](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.mdh34.hackup/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.mdh34.hackup)<br>
[![com.github.mdh34.quickdocs](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.mdh34.quickdocs/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.mdh34.quickdocs)<br>
[![com.github.mirkobrombin.bottles](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.mirkobrombin.bottles/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.mirkobrombin.bottles)<br>
[![com.github.mohelm97.screenrecorder](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.mohelm97.screenrecorder/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.mohelm97.screenrecorder)<br>
[![com.github.muriloventuroso.easyssh](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.muriloventuroso.easyssh/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.muriloventuroso.easyssh)<br>
[![com.github.muriloventuroso.givemelyrics](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.muriloventuroso.givemelyrics/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.muriloventuroso.givemelyrics)<br>
[![com.github.muriloventuroso.pdftricks](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.muriloventuroso.pdftricks/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.muriloventuroso.pdftricks)<br>
[![com.github.naaando.lyrics](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.naaando.lyrics/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.naaando.lyrics)<br>
[![com.github.naaando.rush](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.naaando.rush/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.naaando.rush)<br>
[![com.github.needle-and-thread.vocal](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.needle-and-thread.vocal/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.needle-and-thread.vocal)<br>
[![com.github.padjis.gcron](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.padjis.gcron/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.padjis.gcron)<br>
[![com.github.padjis.ghistory](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.padjis.ghistory/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.padjis.ghistory)<br>
[![com.github.panosx2.brightness](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.panosx2.brightness/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.panosx2.brightness)<br>
[![com.github.parnold-x.nasc](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.parnold-x.nasc/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.parnold-x.nasc)<br>
[![com.github.parnold-x.sudoku](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.parnold-x.sudoku/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.parnold-x.sudoku)<br>
[![com.github.parnold-x.timer](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.parnold-x.timer/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.parnold-x.timer)<br>
[![com.github.peteruithoven.resizer](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.peteruithoven.resizer/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.peteruithoven.resizer)<br>
[![com.github.phase1geo.minder](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.phase1geo.minder/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.phase1geo.minder)<br>
[![com.github.phase1geo.outliner](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.phase1geo.outliner/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.phase1geo.outliner)<br>
[![com.github.philip-scott.notes-up](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.philip-scott.notes-up/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.philip-scott.notes-up)<br>
[![com.github.philip-scott.spice-up](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.philip-scott.spice-up/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.philip-scott.spice-up)<br>
[![com.github.philip-scott.wallpaperize](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.philip-scott.wallpaperize/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.philip-scott.wallpaperize)<br>
[![com.github.plugarut.pwned-checker](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.plugarut.pwned-checker/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.plugarut.pwned-checker)<br>
[![com.github.raibtoffoletto.litteris](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.raibtoffoletto.litteris/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.raibtoffoletto.litteris)<br>
[![com.github.rajkumaar23.badgie](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.rajkumaar23.badgie/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.rajkumaar23.badgie)<br>
[![com.github.ranfdev.raddiu](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.ranfdev.raddiu/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.ranfdev.raddiu)<br>
[![com.github.rapidfingers.translator](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.rapidfingers.translator/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.rapidfingers.translator)<br>
[![com.github.rickybas.date-countdown](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.rickybas.date-countdown/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.rickybas.date-countdown)<br>
[![com.github.rkoesters.xkcd-gtk](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.rkoesters.xkcd-gtk/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.rkoesters.xkcd-gtk)<br>
[![com.github.robertsanseries.ciano](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.robertsanseries.ciano/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.robertsanseries.ciano)<br>
[![com.github.ronnydo.colorpicker](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.ronnydo.colorpicker/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.ronnydo.colorpicker)<br>
[![com.github.ronnydo.wammer](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.ronnydo.wammer/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.ronnydo.wammer)<br>
[![com.github.ryanafrish7.satellite](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.ryanafrish7.satellite/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.ryanafrish7.satellite)<br>
[![com.github.ryonakano.konbucase](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.ryonakano.konbucase/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.ryonakano.konbucase)<br>
[![com.github.ryonakano.reco](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.ryonakano.reco/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.ryonakano.reco)<br>
[![com.github.santileortiz.iconoscope](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.santileortiz.iconoscope/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.santileortiz.iconoscope)<br>
[![com.github.sergius02.qrit](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.sergius02.qrit/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.sergius02.qrit)<br>
[![com.github.sergius02.sherlock](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.sergius02.sherlock/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.sergius02.sherlock)<br>
[![com.github.sgpthomas.hourglass](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.sgpthomas.hourglass/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.sgpthomas.hourglass)<br>
[![com.github.skarva.lockbox](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.skarva.lockbox/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.skarva.lockbox)<br>
[![com.github.spheras.desktopfolder](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.spheras.desktopfolder/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.spheras.desktopfolder)<br>
[![com.github.stsdc.monitor](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.stsdc.monitor/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.stsdc.monitor)<br>
[![com.github.subhadeepjasu.pebbles](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.subhadeepjasu.pebbles/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.subhadeepjasu.pebbles)<br>
[![com.github.tenderowl.norka](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.tenderowl.norka/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.tenderowl.norka)<br>
[![com.github.timecraft.js-test](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.timecraft.js-test/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.timecraft.js-test)<br>
[![com.github.timecraft.notifier](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.timecraft.notifier/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.timecraft.notifier)<br>
[![com.github.tkashkin.boiler](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.tkashkin.boiler/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.tkashkin.boiler)<br>
[![com.github.torikulhabib.mindi](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.torikulhabib.mindi/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.torikulhabib.mindi)<br>
[![com.github.torikulhabib.niki](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.torikulhabib.niki/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.torikulhabib.niki)<br>
[![com.github.torikulhabib.nino](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.torikulhabib.nino/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.torikulhabib.nino)<br>
[![com.github.treagod.spectator](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.treagod.spectator/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.treagod.spectator)<br>
[![com.github.tvale.xkcdesktop](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.tvale.xkcdesktop/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.tvale.xkcdesktop)<br>
[![com.github.writeas.writeas-gtk](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.writeas.writeas-gtk/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.writeas.writeas-gtk)<br>
[![com.github.z0o0p.alohomora](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.z0o0p.alohomora/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.z0o0p.alohomora)<br>
[![com.github.zelikos.rannum](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.zelikos.rannum/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.zelikos.rannum)<br>
[![com.github.ztefn.haguichi](https://github.com/meisenzahl/deb2flatpak/workflows/com.github.ztefn.haguichi/badge.svg)](https://github.com/meisenzahl/deb2flatpak/actions?query=workflow%3Acom.github.ztefn.haguichi)<br>
