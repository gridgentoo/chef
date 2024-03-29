# chef

Управление конфигурацией Серверов [до 50 000 конфигов … на один сервер]
Но при активном участии Facebook'а, которые управляют, наверное, самой большой в мире инсталляцией Chef'а, система была переписана на Erlang + PostgreSQL.

https://sdtimes.com/opscode-unleashes-new-generation-of-chef/

“Chef 11 is a powerful automation platform that allows us to create unprecedented utility supercomputers from 50 to 50,000 cores.

Согласно заявлению Opscode, благодаря изменениям требования к оперативной памяти уменьшились в 10 раз, а масштабируемость системы увеличилась в 4 раза (до 10 000 клиентов на один сервер).

Система управления конфигурацией Chef написана на языках Ruby и Erlang, и предлагает предметно-ориентированный язык для создания инструкций ("рецептов"). Chef может применяться для централизованного изменения конфигурации и автоматизации управления приложениями (установка, обновление, удаление, запуск) в серверных парках различного размера и облачных инфраструктурах. В том числе поддерживается автоматизация развёртывания начинки новых серверов в облачных окружениях Amazon EC2, Rackspace, Google Cloud Platform, Oracle Cloud, OpenStack и Microsoft Azure. Решения на базе Chef применяются компаниями Facebook, Amazon и HP. Управляющие узлы Chef могут быть развёрнуты в дистрибутивах на основе RHEL и Ubuntu. В качестве объектов управления поддерживаются все популярные Linux-дистрибутивы, macOS, FreeBSD, AIX, Solaris и Windows.


# Chef Infra
Ссылка на оригинальный репозиторий
https://github.com/chef/chef

[![Code Climate](https://codeclimate.com/github/chef/chef.svg)](https://codeclimate.com/github/chef/chef)
[![Build Status](https://badge.buildkite.com/c82093430ceec7d27af05febb9dcafe3aa331fff9d74c0ab9d.svg?branch=master)](https://buildkite.com/chef-oss/chef-chef-master-verify)
[![Gem Version](https://badge.fury.io/rb/chef.svg)](https://badge.fury.io/rb/chef)
[![](https://img.shields.io/badge/Release%20Policy-Cadence%20Release-brightgreen.svg)](https://github.com/chef/chef/blob/v15.2.21/docs/dev/design_documents/client_release_cadence.md)

**Umbrella Project**: [Chef Infra](https://github.com/chef/chef-oss-practices/blob/master/projects/chef-infra.md)

**Project State**: [Active](https://github.com/chef/chef-oss-practices/blob/master/repo-management/repo-states.md#active)

**Issues [Response Time Maximum](https://github.com/chef/chef-oss-practices/blob/master/repo-management/repo-states.md)**: 14 days

**Pull Request [Response Time Maximum](https://github.com/chef/chef-oss-practices/blob/master/repo-management/repo-states.md)**: 14 days

## Getting Started

Chef Infra is a configuration management tool designed to bring automation to your entire infrastructure.

### Want to try Chef Infra?

For Chef Infra usage, please refer to our [Learn Chef Rally](https://learn.chef.io/) website, which includes module-based training for Chef Infra, as well as Automate, Habitat, and InSpec.

Other useful resources for Chef Infra users:

- Documentation: <https://docs.chef.io>
- Source: <https://github.com/chef/chef/tree/master>
- Tickets/Issues: <https://github.com/chef/chef/issues>
- Slack: [Chef Community Slack](https://community-slack.chef.io/)
- Mailing list: <https://discourse.chef.io>

## Reporting Issues

Issues can be reported by using [GitHub Issues](https://github.com/chef/chef/issues).

Note that this repository is primarily for reporting issues in the chef-client itself. For reporting issues against other Chef projects, please look up the appropriate repository. If you're unsure where to submit an issue, please ask in the #chef-dev channel in [Chef Community Slack](https://community-slack.chef.io/).

## How We Build & Release Chef

For information on how a contribution goes from PR to released package, see [How Chef Infra Is Built](docs/dev/design_documents/how_chef_is_tested_and_built.md)

To learn more about our monthly feature releases and yearly major releases, see [Chef Infra Release and Support Schedule](./docs/dev/policy/release_and_support_schedule.md).

## Getting Involved

We'd love to have your help developing Chef Infra. See our [Contributing Document](./CONTRIBUTING.md) for more information on getting started.

## License and Copyright

Copyright 2008-2019, Chef Software, Inc.

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

