# Governance for Pyro, NumPyro, and related projects

Pyro is owned by the [LF AI Foundation](https://wiki.lfaidata.foundation/display/PYRO/Pyro+Home).

## Charter

See Pyro's [Technical Charter](https://wiki.lfaidata.foundation/download/attachments/7733298/Pyro%20Project%20Technical%20Charter%201-7-2020.pdf?version=1&modificationDate=1580158662000&api=v2).

## Code owners

When proposing changes to Pyro projects we recommend cc'ing the following owners.
For small changes, feel free to open up a PR directly.
For large changes we recommend opening a github issue for discussion.
For very large design changes we recommend creating a [design document](https://github.com/pyro-ppl/pyro/wiki/Design-Docs) for discussion.

- [Pyro](https://github.com/pyro-ppl/pyro) is owned by
  @fritzo @eb8680 @martinjankowiak @fehiepsi @neerajprad @stefanwebb @jpchen
  - `pyro.poutine` is mainly owned by @eb8680
  - `pyro.distributions` is mainly owned by @fritzo and @neerajprad
  - `pyro.distributions.transforms` is owned by @stefanwebb
  - `pyro.contrib.gp` is owned by @fehiepsi
  - `pyro.contrib.forecast` is owned by @fritzo and @martinjankowiak
  - `pyro.contrib.epidemiology` is owned by @fritzo
  - `pyro.contrib.funsor` is owned by @eb8680

- [NumPyro](https://github.com/pyro-ppl/numpyro) is owned by
  @fehiepsi and @neerajprad

- [Funsor](https://github.com/pyro-ppl/funsor) is owned by
  @eb8680 and @fritzo

For other repos see git commit history.

## Technical Steering Committee

Pyro development is governed by the Technical Steering Committee (TSC).

- Eli Bingham (@eb8680)
- Jonathan P. Chen (@jpchen)
- Martin Jankowiak (@martinjankowiak)
- Fritz Obermeyer (@fritzo) - Chair
- Du Phan (@fehiepsi)
- Neeraj Pradhan (@neerajprad)
- Stefan Webb (@stefanwebb)
