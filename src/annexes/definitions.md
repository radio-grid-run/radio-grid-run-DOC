# Glossary and definitions

## Base

Base station manned by a radio operator with which teams must communicate to validate a contact.

## Team

A team competing in the game. It is made up of several members.

## Contact

A radio exchange between the base station and a team in which the team's position is transmitted in form of a grid square locator (basically a code). Contacts must take place during one of the round's appointments.

## Location

An activated location is a geographical point from which the team has successfully made radio contact with the base.

## Territory

A team's territory is the area delimited by the geographical coordinates from which it has succeeded in transmitting its position to the base.

## Rendezvous

A window of time during which the base responds to teams to validate contacts. These appointments have a defined duration and are limited in number during a round.

## Operator

The operator who answers by radio from the base to the teams calls.

## Grid Square Locator

There are several different ways to implement a code that reference a geographical position. For the moment, we suggest to use the 
3-word code ([what3words](https://what3words.com)) such as ``///coeditor.visiting.paradisiac`` which corresponds to a 3-meter square space. It is associated with a WG84 coordinate using an [API](https://developer.what3words.com/public-api/docs) developed by what3words Ltd.

In the future, we plan to simplify this system by using a predefined local square grid system that would cover only a small perimeters around the base. The WGS84 geodetic position of the teams is in this case deduced by using the base reference position.
