.. Multi-agents Systems documentation master file, created by
   sphinx-quickstart on Sat Oct 19 14:38:02 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Intelligent agents in Distributed Systems
================================================

Multi-Agents 
------------
Multi-Agent Systems are systems composed by a number of agents interacting through an environment. Therefore it covers anything from computer interacting in a network to the financial market. Here we will try to focus on the distributed aspect of those systems and also it's applications in Computer Science.

Now that we know what is a Multi-Agent System (MAS) we need to explain what an agent is. An agent have the following properties:
    * It have some degree of autonomy
    * It must be decentralized
    * It have a limited view/understanding of the world (local view)
    * It might be purposeful
        * If an agent doesn't seek a goal we call it a passive agent
        * If the agent have a goal we call it an active agent
            * Active agents can be clustered as rationals if they always act optimally or irrationals if they don't. 
            * A purposeful agent might follow simple reasoning rules or complex reasoning calculations, or even be behavioral (act in a more natural way)

There is a concept that have a considerable intersection with MAS that is Agent-Based Models (ABM). ABM's are models of systems involving many agents, usually those agents follow simple rules (thanks to the KISS way of thinking, Keep It Simple Stupid!). The biggest difference here is that ABM are used to understand complex behavior that comes from simple pieces working together, those models are created to understand a phenomena while MAS are created to solve some problem.

Applications
------------

Multi-agent system have applications in many fields. In science we usually work with ABM, because we try to explain certain phenomena and predict others. In engineering we use MAS to create all kind of solutions. Internet and any computer network can be seen as a multi-agent system as long it is not a single process monopolizing the machines.

Virtues
-------

Multi-Agent Systems have some intrinsic advantages over monolithic systems (system with only one agent):
    * Scalable
    * Usually fast self-recovery and fault tolerance due to the redundancy of the components
    * This kind of systems also tend to be flexible, because it's easy to add or modify an agent.
    * Self-organization and self-steering (even with simple agents)
    * When talking about simulation, it's parallel and/or distributed implementation usually is straight forward

Drawbacks
---------

It can be processing intensive, and not all problems are easily seen as multi-agent problems. Moreover some systems can become complex and lead us to some unpredictable results (See the Corrupted Blood Incident bellow).


Artificial intelligence, problems approached with this concept
--------------------------------------------------------------
Classic Artificial Intelligence doesn't deal with the "social" aspect of agents. In the classic view there is just the agent and the outside world, thus we just concern about creating an agent to perform a specific task.

How to implement this?
----------------------
We have many languages out there, but still need a more robust and general framework and test units.

What programing languages have been developed to implement those concepts
=========================================================================

Applications in other sciences
------------------------------
Multi-Agent Systems aren't restricted only to the Computer Science domain, it is also sedimented in other fields of knowledge like Economics, Ecology, Logic and even Social Sciences.

Contributions from other sciences (besides computer science)
============================================================

Complex and unexpected behavior - The Corrupted Blood Incident
--------------------------------------------------------------
On September 13, 2005 an mortal disease caused by Hakkar's curse spread out of control devastating the biggest towns in World of Warcraft, the worldwide MMORG. It was caused by a bug, the disease was intended to kill the players characters in a specific area (Zul'Gurub) but due it's easy to spread and the fact that minions and pets could be infected allowed the disease to went out of control.

Many epidemiologist think it was an interesting (although accidental) study case, because the current models use mathematical rules to simulate human behavior, what is not so accurate. In this event we were able to see that many players with healing abilities volunteered to help the infected ones, some players (afterwards called the World of Warcraft terrorists) found creative ways to spread the disease faster and thus cause even more destruction.

It is an awesome example of how a small change in a Multi-Agent System can lead to a instability situation, not due to the program but due to the system itself. The bug doesn't escaped out of control due to a player (human) interference but the non-players characters itselves.

Example of cool application - Semantic Web
------------------------------------------

Bibliography
============

http://www.springer.com/computer/swe/book/978-0-387-24568-3
http://en.wikipedia.org/wiki/Multi-agent_system
http://en.wikipedia.org/wiki/Corrupted_Blood_incident
http://www.slideshare.net/ToniMorenoURV/introduction-to-agents-and-multiagent-systems

.. toctree::
   :maxdepth: 2

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

