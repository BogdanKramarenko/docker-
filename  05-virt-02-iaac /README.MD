
# **ЗАДАНИЕ 1**

**1)Опишите своими словами основные преимущества применения на практике IaaC паттернов.**
Принцип неприрывной  интеграции позволяет достаточно быстро находить ошибки в коде,так же за счет постоянного тестирования небольшими объемами. Непрерывная доставка позволяет легко исправить или откатиться на недавнее состояние в случае ошибок.

**2)Какой из принципов IaaC является основополагающим?**
Получение стабильного и предсказуемого результата каждый раз при использовании(запуске) кода.

# ЗАДАНИЕ 2

**1)Чем Ansible выгодно отличается от других систем управление конфигурациями?**
Его основные преимущества это использование SSH инфраструктуры без установки дополнительного окружения, а также наличие большого количества модулей.

**2)Какой, на ваш взгляд, метод работы систем конфигурации более надёжный push или pull?**
Управление push мне кажется более надёжным. В этом случае одновременно получаем нужные конфигурации на машинах в нужный момент времени.

# ЗАДАНИЕ 3
 1)Vagrant 
`bogdankramarenko@MacBook-Pro-Bogdan ~ % vagrant --version
Vagrant 2.3.1`

 2)Ansible
bogdankramarenko@MacBook-Pro-Bogdan ~ % ansible --version
`ansible [core 2.13.5]
  config file = None
  configured module search path = ['/Users/bogdankramarenko/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
  ansible python module location = /Library/Python/3.9/site-packages/ansible
  ansible collection location = /Users/bogdankramarenko/.ansible/collections:/usr/share/ansible/collections
  executable location = /usr/local/bin/ansible
  python version = 3.9.6 (default, Aug  5 2022, 15:21:02) [Clang 14.0.0 (clang-1400.0.29.102)]
  jinja version = 3.1.2
  libyaml = True`

3)Virtual Box
к сожалению поставить не могу так как работаю на mac c m1 pro чипом
