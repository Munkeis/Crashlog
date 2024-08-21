---- Minecraft Crash Report ----
// I bet Cylons wouldn't have this problem.

Time: 2024-08-21 20:02:38
Description: Rendering entity in world

java.lang.ClassCastException: class fi.dy.masa.litematica.world.WorldSchematic cannot be cast to class net.minecraft.client.multiplayer.ClientLevel (fi.dy.masa.litematica.world.WorldSchematic is in module forgematica@0.1.5-mc1.20.1 of loader 'TRANSFORMER' @7f79edee; net.minecraft.client.multiplayer.ClientLevel is in module minecraft@1.20.1 of loader 'TRANSFORMER' @7f79edee)
	at shcm.shsupercm.forge.citresewn.ActiveCITs.getItemModelCached(ActiveCITs.java:137) ~[citresewn-1.20.1-4.jar%23182!/:1.20.1-4] {re:mixin,re:classloading}
	at net.minecraft.client.renderer.entity.ItemRenderer.handler$zbi000$getItemModel(ItemRenderer.java:1039) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citresewn.mixins.json:citenchantment.ItemRendererMixin,pl:mixin:APP:citresewn.mixins.json:cititem.ItemRendererMixin,pl:mixin:APP:mixins.render.blend.replaymod.json:ItemRendererAccessor,pl:mixin:APP:exposure-common.mixins.json:ItemRendererMixin,pl:mixin:APP:embeddium.mixins.json:features.render.model.item.ItemRendererMixin,pl:mixin:APP:quark.mixins.json:client.ItemRendererMixin,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinItemRenderer,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemRenderer.m_174264_(ItemRenderer.java) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citresewn.mixins.json:citenchantment.ItemRendererMixin,pl:mixin:APP:citresewn.mixins.json:cititem.ItemRendererMixin,pl:mixin:APP:mixins.render.blend.replaymod.json:ItemRendererAccessor,pl:mixin:APP:exposure-common.mixins.json:ItemRendererMixin,pl:mixin:APP:embeddium.mixins.json:features.render.model.item.ItemRendererMixin,pl:mixin:APP:quark.mixins.json:client.ItemRendererMixin,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinItemRenderer,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemRenderer.m_269491_(ItemRenderer.java:225) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citresewn.mixins.json:citenchantment.ItemRendererMixin,pl:mixin:APP:citresewn.mixins.json:cititem.ItemRendererMixin,pl:mixin:APP:mixins.render.blend.replaymod.json:ItemRendererAccessor,pl:mixin:APP:exposure-common.mixins.json:ItemRendererMixin,pl:mixin:APP:embeddium.mixins.json:features.render.model.item.ItemRendererMixin,pl:mixin:APP:quark.mixins.json:client.ItemRendererMixin,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinItemRenderer,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemRenderer.m_269128_(ItemRenderer.java:220) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citresewn.mixins.json:citenchantment.ItemRendererMixin,pl:mixin:APP:citresewn.mixins.json:cititem.ItemRendererMixin,pl:mixin:APP:mixins.render.blend.replaymod.json:ItemRendererAccessor,pl:mixin:APP:exposure-common.mixins.json:ItemRendererMixin,pl:mixin:APP:embeddium.mixins.json:features.render.model.item.ItemRendererMixin,pl:mixin:APP:quark.mixins.json:client.ItemRendererMixin,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinItemRenderer,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemFrameRenderer.m_7392_(ItemFrameRenderer.java:96) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemFrameRenderer.m_7392_(ItemFrameRenderer.java:30) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_114384_(EntityRenderDispatcher.java:140) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.render.replaymod.json:MixinRenderManager,pl:mixin:APP:mixins.oculus.json:MixinEntityRenderDispatcher,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinEntityRenderDispatcher,pl:mixin:APP:mixins.oculus.compat.sodium.json:copyEntity.shadows.EntityRenderDispatcherMixin,pl:mixin:APP:mixins.oculus.compat.sodium.json:vertex_format.entity.MixinEntityRenderDispatcher,pl:mixin:A,pl:runtimedistcleaner:A}
	at fi.dy.masa.litematica.render.schematic.WorldRendererSchematic.renderEntities(WorldRendererSchematic.java:697) ~[Forgematica-0.1.5-mc1.20.1.jar%23192!/:?] {re:mixin,re:classloading}
	at fi.dy.masa.litematica.render.LitematicaRenderer.piecewiseRenderEntities(LitematicaRenderer.java:401) ~[Forgematica-0.1.5-mc1.20.1.jar%23192!/:?] {re:mixin,re:classloading}
	at net.minecraft.client.renderer.LevelRenderer.handler$zii000$onPostRenderEntities(LevelRenderer.java:11141) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.LevelRenderer.m_109599_(LevelRenderer.java:1235) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109089_(GameRenderer.java:1126) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:909) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1146) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.3.4.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:flywheel.mixins.json:ClientMainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Suspected Mods: 
	Forgematica (forgematica), Version: 0.1.5-mc1.20.1
		at TRANSFORMER/forgematica@0.1.5-mc1.20.1/fi.dy.masa.litematica.render.schematic.WorldRendererSchematic.renderEntities(WorldRendererSchematic.java:697)

	CIT Resewn (citresewn), Version: 1.20.1-4
		at TRANSFORMER/citresewn@1.20.1-4/shcm.shsupercm.forge.citresewn.ActiveCITs.getItemModelCached(ActiveCITs.java:137)
Stacktrace:
	at shcm.shsupercm.forge.citresewn.ActiveCITs.getItemModelCached(ActiveCITs.java:137) ~[citresewn-1.20.1-4.jar%23182!/:1.20.1-4] {re:mixin,re:classloading}
	at net.minecraft.client.renderer.entity.ItemRenderer.handler$zbi000$getItemModel(ItemRenderer.java:1039) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citresewn.mixins.json:citenchantment.ItemRendererMixin,pl:mixin:APP:citresewn.mixins.json:cititem.ItemRendererMixin,pl:mixin:APP:mixins.render.blend.replaymod.json:ItemRendererAccessor,pl:mixin:APP:exposure-common.mixins.json:ItemRendererMixin,pl:mixin:APP:embeddium.mixins.json:features.render.model.item.ItemRendererMixin,pl:mixin:APP:quark.mixins.json:client.ItemRendererMixin,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinItemRenderer,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemRenderer.m_174264_(ItemRenderer.java) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citresewn.mixins.json:citenchantment.ItemRendererMixin,pl:mixin:APP:citresewn.mixins.json:cititem.ItemRendererMixin,pl:mixin:APP:mixins.render.blend.replaymod.json:ItemRendererAccessor,pl:mixin:APP:exposure-common.mixins.json:ItemRendererMixin,pl:mixin:APP:embeddium.mixins.json:features.render.model.item.ItemRendererMixin,pl:mixin:APP:quark.mixins.json:client.ItemRendererMixin,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinItemRenderer,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemRenderer.m_269491_(ItemRenderer.java:225) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citresewn.mixins.json:citenchantment.ItemRendererMixin,pl:mixin:APP:citresewn.mixins.json:cititem.ItemRendererMixin,pl:mixin:APP:mixins.render.blend.replaymod.json:ItemRendererAccessor,pl:mixin:APP:exposure-common.mixins.json:ItemRendererMixin,pl:mixin:APP:embeddium.mixins.json:features.render.model.item.ItemRendererMixin,pl:mixin:APP:quark.mixins.json:client.ItemRendererMixin,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinItemRenderer,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemRenderer.m_269128_(ItemRenderer.java:220) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:citresewn.mixins.json:citenchantment.ItemRendererMixin,pl:mixin:APP:citresewn.mixins.json:cititem.ItemRendererMixin,pl:mixin:APP:mixins.render.blend.replaymod.json:ItemRendererAccessor,pl:mixin:APP:exposure-common.mixins.json:ItemRendererMixin,pl:mixin:APP:embeddium.mixins.json:features.render.model.item.ItemRendererMixin,pl:mixin:APP:quark.mixins.json:client.ItemRendererMixin,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinItemRenderer,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemFrameRenderer.m_7392_(ItemFrameRenderer.java:96) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.ItemFrameRenderer.m_7392_(ItemFrameRenderer.java:30) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_114384_(EntityRenderDispatcher.java:140) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.render.replaymod.json:MixinRenderManager,pl:mixin:APP:mixins.oculus.json:MixinEntityRenderDispatcher,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinEntityRenderDispatcher,pl:mixin:APP:mixins.oculus.compat.sodium.json:copyEntity.shadows.EntityRenderDispatcherMixin,pl:mixin:APP:mixins.oculus.compat.sodium.json:vertex_format.entity.MixinEntityRenderDispatcher,pl:mixin:A,pl:runtimedistcleaner:A}
	at fi.dy.masa.litematica.render.schematic.WorldRendererSchematic.renderEntities(WorldRendererSchematic.java:697) ~[Forgematica-0.1.5-mc1.20.1.jar%23192!/:?] {re:mixin,re:classloading}
	at fi.dy.masa.litematica.render.LitematicaRenderer.piecewiseRenderEntities(LitematicaRenderer.java:401) ~[Forgematica-0.1.5-mc1.20.1.jar%23192!/:?] {re:mixin,re:classloading}
	at net.minecraft.client.renderer.LevelRenderer.handler$zii000$onPostRenderEntities(LevelRenderer.java:11141) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.LevelRenderer.m_109599_(LevelRenderer.java:1235) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109089_(GameRenderer.java:1126) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
-- Entity being rendered --
Details:
	Entity Type: minecraft:item_frame (net.minecraft.world.entity.decoration.ItemFrame)
	Entity ID: 23
	Entity Name: Item Frame
	Entity's Exact location: -103.50, 109.03, -664.50
	Entity's Block location: World: (-104,109,-665), Section: (at 8,13,7 in -7,6,-42; chunk contains blocks -112,-64,-672 to -97,319,-657), Region: (-1,-2; contains chunks -32,-64 to -1,-33, blocks -512,-64,-1024 to -1,319,-513)
	Entity's Momentum: 0.00, 0.00, 0.00
	Entity's Passengers: []
	Entity's Vehicle: null
Stacktrace:
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_114384_(EntityRenderDispatcher.java:140) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.render.replaymod.json:MixinRenderManager,pl:mixin:APP:mixins.oculus.json:MixinEntityRenderDispatcher,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinEntityRenderDispatcher,pl:mixin:APP:mixins.oculus.compat.sodium.json:copyEntity.shadows.EntityRenderDispatcherMixin,pl:mixin:APP:mixins.oculus.compat.sodium.json:vertex_format.entity.MixinEntityRenderDispatcher,pl:mixin:A,pl:runtimedistcleaner:A}
	at fi.dy.masa.litematica.render.schematic.WorldRendererSchematic.renderEntities(WorldRendererSchematic.java:697) ~[Forgematica-0.1.5-mc1.20.1.jar%23192!/:?] {re:mixin,re:classloading}
	at fi.dy.masa.litematica.render.LitematicaRenderer.piecewiseRenderEntities(LitematicaRenderer.java:401) ~[Forgematica-0.1.5-mc1.20.1.jar%23192!/:?] {re:mixin,re:classloading}
	at net.minecraft.client.renderer.LevelRenderer.handler$zii000$onPostRenderEntities(LevelRenderer.java:11141) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.LevelRenderer.m_109599_(LevelRenderer.java:1235) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109089_(GameRenderer.java:1126) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:909) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1146) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.3.4.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:flywheel.mixins.json:ClientMainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- Renderer details --
Details:
	Assigned renderer: net.minecraft.client.renderer.entity.ItemFrameRenderer@3519b50a
	Location: 6.28,-0.96,4.05 - World: (6,-1,4), Section: (at 6,15,4 in 0,-1,0; chunk contains blocks 0,-64,0 to 15,319,15), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,-64,0 to 511,319,511)
	Rotation: 0.0
	Delta: 1.0
Stacktrace:
	at net.minecraft.client.renderer.entity.EntityRenderDispatcher.m_114384_(EntityRenderDispatcher.java:140) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.render.replaymod.json:MixinRenderManager,pl:mixin:APP:mixins.oculus.json:MixinEntityRenderDispatcher,pl:mixin:APP:mixins.oculus.json:entity_render_context.MixinEntityRenderDispatcher,pl:mixin:APP:mixins.oculus.compat.sodium.json:copyEntity.shadows.EntityRenderDispatcherMixin,pl:mixin:APP:mixins.oculus.compat.sodium.json:vertex_format.entity.MixinEntityRenderDispatcher,pl:mixin:A,pl:runtimedistcleaner:A}
	at fi.dy.masa.litematica.render.schematic.WorldRendererSchematic.renderEntities(WorldRendererSchematic.java:697) ~[Forgematica-0.1.5-mc1.20.1.jar%23192!/:?] {re:mixin,re:classloading}
	at fi.dy.masa.litematica.render.LitematicaRenderer.piecewiseRenderEntities(LitematicaRenderer.java:401) ~[Forgematica-0.1.5-mc1.20.1.jar%23192!/:?] {re:mixin,re:classloading}
	at net.minecraft.client.renderer.LevelRenderer.handler$zii000$onPostRenderEntities(LevelRenderer.java:11141) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.LevelRenderer.m_109599_(LevelRenderer.java:1235) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109089_(GameRenderer.java:1126) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:909) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1146) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:718) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.3.4.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:flywheel.mixins.json:ClientMainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- Affected level --
Details:
	All players: 1 total; [LocalPlayer['Munkei'/1, l='ClientLevel', x=-109.78, y=108.37, z=-668.55]]
	Chunk stats: 961, 609
	Level dimension: minecraft:overworld
	Level spawn location: World: (1474,112,1786), Section: (at 2,0,10 in 92,7,111; chunk contains blocks 1472,-64,1776 to 1487,319,1791), Region: (2,3; contains chunks 64,96 to 95,127, blocks 1024,-64,1536 to 1535,319,2047)
	Level time: 3466589 game time, 1600 day time
	Server brand: forge
	Server type: Integrated singleplayer server
Stacktrace:
	at net.minecraft.client.multiplayer.ClientLevel.m_6026_(ClientLevel.java:455) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:APP:embeddium.mixins.json:features.render.world.ClientLevelMixin,pl:mixin:APP:flywheel.mixins.json:ClientLevelMixin,pl:mixin:APP:citadel.mixins.json:client.ClientLevelMixin,pl:mixin:APP:mixins.recording.replaymod.json:MixinWorldClient,pl:mixin:APP:mixins.replay.replaymod.json:ClientWorldAccessor,pl:mixin:APP:mixins.replay.replaymod.json:MixinWorldClient,pl:mixin:APP:forgematica.mixins.json:MixinClientWorld,pl:mixin:APP:mixins.oculus.vertexformat.json:block_rendering.MixinClientLevel,pl:mixin:APP:embeddium.mixins.json:core.world.biome.ClientWorldMixin,pl:mixin:APP:embeddium.mixins.json:core.world.map.ClientWorldMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91354_(Minecraft.java:2319) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:735) ~[client-1.20.1-20230612.114412-srg.jar%23202!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:218) ~[1.20.1-forge-47.3.4.jar:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:APP:flywheel.mixins.json:ClientMainMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.runTarget(CommonLaunchHandler.java:111) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonLaunchHandler.clientService(CommonLaunchHandler.java:99) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$makeService$0(CommonClientLaunchHandler.java:25) ~[fmlloader-1.20.1-47.3.4.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:108) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:78) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) ~[modlauncher-10.0.9.jar:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) ~[bootstraplauncher-1.1.2.jar:?] {}


-- Last reload --
Details:
	Reload number: 1
	Reload reason: initial
	Finished: Yes
	Packs: mod_resources, vanilla, file/Mizunos 16 Craft JE_1.19.4-1.1, file/Pixel Paintings - Cottagecore Collection, file/Supa Lilies 1.16.4, file/Hananacraft v1.3.4, file/Mizunos 16 Craft JE CIT_1.20.1-1.0_230720, file/Mizunos-16-Craft-CIT-Pack-16x-Invisible-Item-Frame-1.18.2(1), file/GARDEN BREEZE 1.1, file/blank-e60 - no moon or sun, replaymod_lang

-- System Details --
Details:
	Minecraft Version: 1.20.1
	Minecraft Version ID: 1.20.1
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.8, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 1832260048 bytes (1747 MiB) / 5771362304 bytes (5504 MiB) up to 8589934592 bytes (8192 MiB)
	CPUs: 16
	Processor Vendor: AuthenticAMD
	Processor Name: AMD Ryzen 7 5800X 8-Core Processor             
	Identifier: AuthenticAMD Family 25 Model 33 Stepping 2
	Microarchitecture: Zen 3
	Frequency (GHz): 3.80
	Number of physical packages: 1
	Number of physical CPUs: 8
	Number of logical CPUs: 16
	Graphics card #0 name: NVIDIA GeForce RTX 3080
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x2216
	Graphics card #0 versionInfo: DriverVersion=32.0.15.6081
	Memory slot #0 capacity (MB): 16384.00
	Memory slot #0 clockSpeed (GHz): 3.20
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 16384.00
	Memory slot #1 clockSpeed (GHz): 3.20
	Memory slot #1 type: DDR4
	Memory slot #2 capacity (MB): 16384.00
	Memory slot #2 clockSpeed (GHz): 3.20
	Memory slot #2 type: DDR4
	Memory slot #3 capacity (MB): 16384.00
	Memory slot #3 clockSpeed (GHz): 3.20
	Memory slot #3 type: DDR4
	Virtual memory max (MB): 75150.83
	Virtual memory used (MB): 25035.54
	Swap memory total (MB): 9728.00
	Swap memory used (MB): 0.00
	JVM Flags: 9 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx8G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	Loaded Shaderpack: (off)
	Launched Version: 1.20.1-forge-47.3.4
	Backend library: LWJGL version 3.3.1 build 7
	Backend API: NVIDIA GeForce RTX 3080/PCIe/SSE2 GL version 4.6.0 NVIDIA 560.81, NVIDIA Corporation
	Window size: 1920x1080
	GL Caps: Using framebuffer using OpenGL 3.2
	GL debug messages: 
	Using VBOs: Yes
	Is Modded: Definitely; Client brand changed to 'forge'; Server brand changed to 'forge'
	Type: Integrated Server (map_client.txt)
	Graphics mode: fancy
	Resource Packs: mod_resources, vanilla, file/Mizunos 16 Craft JE_1.19.4-1.1, file/Pixel Paintings - Cottagecore Collection, file/Supa Lilies 1.16.4 (incompatible), file/Hananacraft v1.3.4, file/Mizunos 16 Craft JE CIT_1.20.1-1.0_230720, file/Mizunos-16-Craft-CIT-Pack-16x-Invisible-Item-Frame-1.18.2(1), file/GARDEN BREEZE 1.1, file/blank-e60 - no moon or sun
	Current Language: en_US
	CPU: 16x AMD Ryzen 7 5800X 8-Core Processor 
	Server Running: true
	Player Count: 1 / 8; [ServerPlayer['Munkei'/1, l='ServerLevel[Moss House]', x=-109.78, y=108.37, z=-668.55]]
	Data Packs: mod:terrablender, mod:regions_unexplored (incompatible), mod:biomesoplenty (incompatible), mod:createdeco (incompatible), mod:flywheel, mod:create, mod:fallingleaves, mod:croptopia (incompatible), mod:citadel (incompatible), mod:alexsmobs (incompatible), mod:epherolib (incompatible), mod:mixinextras (incompatible), mod:worldedit (incompatible), mod:iceandfire, mod:exposure, mod:forge, mod:zeta (incompatible), mod:quark (incompatible), mod:dynamictrees (incompatible), mod:dtbop (incompatible), mod:embeddium, vanilla, mod:mafglib, mod:reforgedplaymod (incompatible), mod:oculus, mod:forgematica (incompatible), mod:citresewn (incompatible)
	Enabled Feature Flags: minecraft:vanilla
	World Generation: Stable
	ModLauncher: 10.0.9+10.0.9+main.dcd20f30
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		mixin-0.8.5.jar mixin PLUGINSERVICE 
		eventbus-6.0.5.jar eventbus PLUGINSERVICE 
		fmlloader-1.20.1-47.3.4.jar slf4jfixer PLUGINSERVICE 
		fmlloader-1.20.1-47.3.4.jar object_holder_definalize PLUGINSERVICE 
		fmlloader-1.20.1-47.3.4.jar runtime_enum_extender PLUGINSERVICE 
		fmlloader-1.20.1-47.3.4.jar capability_token_subclass PLUGINSERVICE 
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE 
		fmlloader-1.20.1-47.3.4.jar runtimedistcleaner PLUGINSERVICE 
		modlauncher-10.0.9.jar mixin TRANSFORMATIONSERVICE 
		modlauncher-10.0.9.jar fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		lowcodefml@null
		javafml@null
	Mod List: 
		client-1.20.1-20230612.114412-srg.jar             |Minecraft                     |minecraft                     |1.20.1              |DONE      |Manifest: a1:d4:5e:04:4f:d3:d6:e0:7b:37:97:cf:77:b0:de:ad:4a:47:ce:8c:96:49:5f:0a:cf:8c:ae:b2:6d:4b:8a:3f
		TerraBlender-forge-1.20.1-3.0.1.7.jar             |TerraBlender                  |terrablender                  |3.0.1.7             |DONE      |Manifest: NOSIGNATURE
		RegionsUnexploredForge-0.5.5+1.20.1.jar           |Regions Unexplored            |regions_unexplored            |0.5.5               |DONE      |Manifest: NOSIGNATURE
		BiomesOPlenty-1.20.1-18.0.0.592.jar               |Biomes O' Plenty              |biomesoplenty                 |18.0.0.592          |DONE      |Manifest: NOSIGNATURE
		createdeco-2.0.2-1.20.1-forge.jar                 |Create Deco                   |createdeco                    |2.0.2-1.20.1-forge  |DONE      |Manifest: NOSIGNATURE
		MaFgLib-0.1.11-mc1.20.1.jar                       |MaFgLib                       |mafglib                       |0.1.11-mc1.20.1     |DONE      |Manifest: NOSIGNATURE
		citresewn-1.20.1-4.jar                            |CIT Resewn                    |citresewn                     |1.20.1-4            |DONE      |Manifest: NOSIGNATURE
		flywheel-forge-1.20.1-0.6.10-7.jar                |Flywheel                      |flywheel                      |0.6.10-7            |DONE      |Manifest: NOSIGNATURE
		create-1.20.1-0.5.1.f.jar                         |Create                        |create                        |0.5.1.f             |DONE      |Manifest: NOSIGNATURE
		Fallingleaves-1.20.1-2.1.0.jar                    |Falling Leaves                |fallingleaves                 |2.1.0               |DONE      |Manifest: NOSIGNATURE
		Croptopia-1.20.1-FORGE-3.0.4.jar                  |Croptopia                     |croptopia                     |3.0.4               |DONE      |Manifest: NOSIGNATURE
		citadel-2.4.4-1.20.1.jar                          |Citadel                       |citadel                       |2.4.4               |DONE      |Manifest: NOSIGNATURE
		alexsmobs-1.22.8.jar                              |Alex's Mobs                   |alexsmobs                     |1.22.8              |DONE      |Manifest: NOSIGNATURE
		EpheroLib-1.20.1-FORGE-1.2.0.jar                  |BOZOID                        |epherolib                     |0.1.2               |DONE      |Manifest: NOSIGNATURE
		reforgedplaymod-1.20.1-0.1.jar                    |ReForgedPlay Mod              |reforgedplaymod               |0.1                 |DONE      |Manifest: NOSIGNATURE
		Forgematica-0.1.5-mc1.20.1.jar                    |Forgematica                   |forgematica                   |0.1.5-mc1.20.1      |DONE      |Manifest: NOSIGNATURE
		mixinextras-forge-0.3.5.jar                       |MixinExtras                   |mixinextras                   |0.3.5               |DONE      |Manifest: NOSIGNATURE
		worldedit-mod-7.2.15.jar                          |WorldEdit                     |worldedit                     |7.2.15+6463-5ca4dff |DONE      |Manifest: NOSIGNATURE
		iceandfire-2.1.13-1.20.1-beta-4.jar               |Ice and Fire                  |iceandfire                    |2.1.13-1.20.1-beta-4|DONE      |Manifest: NOSIGNATURE
		exposure-1.20.1-1.7.4-forge.jar                   |Exposure                      |exposure                      |1.7.4               |DONE      |Manifest: NOSIGNATURE
		forge-1.20.1-47.3.4-universal.jar                 |Forge                         |forge                         |47.3.4              |DONE      |Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
		Zeta-1.0-19.jar                                   |Zeta                          |zeta                          |1.0-19              |DONE      |Manifest: NOSIGNATURE
		Quark-4.0-458.jar                                 |Quark                         |quark                         |4.0-458             |DONE      |Manifest: NOSIGNATURE
		DynamicTrees-1.20.1-1.3.0-BETA10.jar              |Dynamic Trees                 |dynamictrees                  |1.20.1-1.3.0-BETA10 |DONE      |Manifest: NOSIGNATURE
		DynamicTreesBOP-1.20.1-3.2.3.jar                  |Dynamic Trees for Biomes o' Pl|dtbop                         |1.20.1-3.2.3        |DONE      |Manifest: NOSIGNATURE
		embeddium-0.3.24+mc1.20.1.jar                     |Embeddium                     |embeddium                     |0.3.24+mc1.20.1     |DONE      |Manifest: NOSIGNATURE
		oculus-mc1.20.1-1.7.0.jar                         |Oculus                        |oculus                        |1.7.0               |DONE      |Manifest: NOSIGNATURE
	Flywheel Backend: GL33 Instanced Arrays
	Crash Report UUID: a15aba78-242e-415a-94e3-a0967e7947da
	FML: 47.3
	Forge: net.minecraftforge:47.3.4
