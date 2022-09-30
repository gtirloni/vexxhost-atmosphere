# Changelog

## [0.3.0](https://github.com/vexxhost/atmosphere/compare/v0.2.2...v0.3.0) (2022-09-28)


### Features

* **ingress:** move to operator ([46475f8](https://github.com/vexxhost/atmosphere/commit/46475f8c98d538d8c194ba9de8b9b926a50193d2))

## [0.2.2](https://github.com/vexxhost/atmosphere/compare/v0.2.1...v0.2.2) (2022-09-27)


### Bug Fixes

* **memcached:** add protocol to service ([c252a9b](https://github.com/vexxhost/atmosphere/commit/c252a9b0db0d61a4745c4177c378d83232fa5c4c))

## [0.2.1](https://github.com/vexxhost/atmosphere/compare/v0.2.0...v0.2.1) (2022-09-27)


### Bug Fixes

* **rabbitmq:** drop terminationGracePeriodSeconds down ([f791801](https://github.com/vexxhost/atmosphere/commit/f791801625f30ae01d457a00cf223565261ec1b4))

## [0.2.0](https://github.com/vexxhost/atmosphere/compare/v0.1.1...v0.2.0) (2022-09-27)


### Features

* migrate cert-mgr + rmq to operator ([e1e1ae4](https://github.com/vexxhost/atmosphere/commit/e1e1ae4075bef7fec6668b5a10e1e847d2a9ff48))
* move pxc to operator ([bdb9774](https://github.com/vexxhost/atmosphere/commit/bdb9774bed5e819a19199bfc6b6f82643c22d6b1))
* move rmq to operator ([196945a](https://github.com/vexxhost/atmosphere/commit/196945a07fc381ca178d0cfab4c42e3500564d3c))
* use server-side apply ([2222854](https://github.com/vexxhost/atmosphere/commit/2222854a76cc4d778ccf092d0ada985ddc7feb18))


### Bug Fixes

* add services to cluster role ([168c264](https://github.com/vexxhost/atmosphere/commit/168c2649d2d5e1184cddae93fac82ca508409f25))
* avoid race condition with csi not up ([2621136](https://github.com/vexxhost/atmosphere/commit/2621136bce9d453d41353acbd653679cb3de0683))
* bump timeout to 300s ([ac0d453](https://github.com/vexxhost/atmosphere/commit/ac0d45336a5510a2dfe65597693adedb18a059b9))
* increase wait timeout ([3ffc33e](https://github.com/vexxhost/atmosphere/commit/3ffc33e751b56fcc632f64afe34e67529da436ce))
* move memcached to operator ([e48a677](https://github.com/vexxhost/atmosphere/commit/e48a6779969e9ad829d9d4366853db0fa5b9be7b))
* slow down API polls ([da561e3](https://github.com/vexxhost/atmosphere/commit/da561e36bcb5f32f3565a3f490fa41d86801e746))
* solve config.toml rendering ([40e63b1](https://github.com/vexxhost/atmosphere/commit/40e63b10f084288e921975825c1f869127620834))
* solve ingress race conditions ([ff5e860](https://github.com/vexxhost/atmosphere/commit/ff5e86011cfdad85af2b4c46931e74358b93af27))
* solve update_object for svc ([3e66870](https://github.com/vexxhost/atmosphere/commit/3e668702b16c6e6eb206b769a98c2332b0b97ecc))
* update role to create pxc ([6203025](https://github.com/vexxhost/atmosphere/commit/6203025ffef4cdc2f55ff2960dbc95475272685f))

## [0.1.1](https://github.com/vexxhost/atmosphere/compare/v0.1.0...v0.1.1) (2022-09-21)


### Bug Fixes

* galaxy.yml metadata ([7505359](https://github.com/vexxhost/atmosphere/commit/7505359ad515ac55e194f20573621e6ffebc4802))

## 0.1.0 (2022-09-21)


### Features

* add simple controller to generate helm values ([12676ed](https://github.com/vexxhost/atmosphere/commit/12676edad82b187b1b2339a3c8f3d64cf5a3b006))
* add value overrides ([0f98213](https://github.com/vexxhost/atmosphere/commit/0f982131350a65dc36d6da5ec9b2e8c60070dea7))
* added operator role ([edc9b87](https://github.com/vexxhost/atmosphere/commit/edc9b87bd580b276bd49448a664a808a819db718))
* clean-up more code for helm repos ([64da5c6](https://github.com/vexxhost/atmosphere/commit/64da5c6b3ac4c2898b145b38bfc64baa0eb552a2))
* **ethtool:** add automatic tuning ([64f84a4](https://github.com/vexxhost/atmosphere/commit/64f84a4f016d33687a1c5d59d000a1113a9aaa40))
* **ethtool:** add initial commit ([34c5b53](https://github.com/vexxhost/atmosphere/commit/34c5b5341ceceeb14f6510fd66f28249c8a2db9b))
* **ethtool:** add podmonitor + basic rules ([b529c33](https://github.com/vexxhost/atmosphere/commit/b529c33e7917ce206099eb2134da5948b5828c47))
* **ethtool:** faster convergence + multiarch image ([25e5f6c](https://github.com/vexxhost/atmosphere/commit/25e5f6c075c31ac87a60e7eb4d542665749faacb))
* move nfd to operator ([52f3feb](https://github.com/vexxhost/atmosphere/commit/52f3feb3562e42904c4bb2e40331461e1abd5a7f))
* switch openstack-helm-infra to atmosphere ([313085b](https://github.com/vexxhost/atmosphere/commit/313085b210532d850c179edf368c8a7beff93b76))


### Bug Fixes

* add helmrelease to cluster role ([4787745](https://github.com/vexxhost/atmosphere/commit/4787745e9ebb23956b0e8d87e9548e953936c3dc))
* add novnc to nova images ([5a4eb80](https://github.com/vexxhost/atmosphere/commit/5a4eb80f73307a3ccab30dd7aa329171cb08cabe))
* commit time ([501dc41](https://github.com/vexxhost/atmosphere/commit/501dc41fd86deeaf67aabdc23a6540f18c6584d0))
* drop extra var ([64b555b](https://github.com/vexxhost/atmosphere/commit/64b555b7b4a8e602d138ab3fe3014843ed3dd0c1))
* enable glance with cinder ([01c78ca](https://github.com/vexxhost/atmosphere/commit/01c78ca2d0e6dc6902bccdc244161a355bf51ee3))
* **ethtool:** add variable for image tag ([29d7134](https://github.com/vexxhost/atmosphere/commit/29d7134e4ed1349f95705037b6065ca1754e9600))
* **ethtool:** fix linting for ethtool ([1f75624](https://github.com/vexxhost/atmosphere/commit/1f7562437962d3153355cc90f3729daa4904a7aa))
* fix tomli import ([50483b4](https://github.com/vexxhost/atmosphere/commit/50483b477b32a88bf852b212d1f7a8dda66472af))
* **glance:** switch to using cinder internal url ([602b116](https://github.com/vexxhost/atmosphere/commit/602b116aebef603b2b87d7bed7daa9e82f4c105a))
* **glance:** use updated image ([5e5de25](https://github.com/vexxhost/atmosphere/commit/5e5de25b8fc618cee8f5b98e68790e512d450f1f))
* improper role permissions ([da4016b](https://github.com/vexxhost/atmosphere/commit/da4016b77b1e4628ec432674fe6cd97a7ec5e81e))
* iscsi/fc for cinder/nova ([fdc71b7](https://github.com/vexxhost/atmosphere/commit/fdc71b73b6ef532a57d8f40472bdde5619a4d799))
* **metrics:** don't wait for entire helmrelease, just deployment ([2a8ce6a](https://github.com/vexxhost/atmosphere/commit/2a8ce6a4011f3e32b48d38b42211181d40be8e99))
* point to v5 api for git ([98ec126](https://github.com/vexxhost/atmosphere/commit/98ec12632fbc8a7bedba1d82957fb5da9d3723af))
* retry flavor creation in ci ([6f85b3a](https://github.com/vexxhost/atmosphere/commit/6f85b3ad2d624b4c6c89c515cb60cdc4879ecd5b))
* stop waiting for kube-prometheus-stack ([b8d3432](https://github.com/vexxhost/atmosphere/commit/b8d34325c00c8f039bc137ba60ebc446bbabe95c))
* switch openstack-exporter to new image repo ([6e24e87](https://github.com/vexxhost/atmosphere/commit/6e24e87d02ad9878db45bed5743f1cdd142f8762))
* use tomli ([ea2e521](https://github.com/vexxhost/atmosphere/commit/ea2e5211c1f1e22c3f2c7504f9cc3aa95a649418))


### Documentation

* add powerstore for nova ([8539edc](https://github.com/vexxhost/atmosphere/commit/8539edcb3cf152b873945e9989c33c7812d5b524))
* update powerstore ([d4098be](https://github.com/vexxhost/atmosphere/commit/d4098bed63f0caed8c5246c668b9a476b9a3b661))