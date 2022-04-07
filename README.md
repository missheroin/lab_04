# lab_04

   **A simple example of a server balancer**.
   
   Balancing type - `round-robbin`.

To test the work of this balancer, you need:
1. Download all files from this repository and move them to one folder.
2. On the command line, write the command:
*      vagrant up
3. Wait until the virtual machines are created and started.
4. After that, enter the command in the command line:
*      ansible-playbook nginx.conf
5. Wait until the playbook is played and the results of its work are displayed.
6. After that, we launch any of our browsers and enter in the search bar:
*      http://192.168.11.113
7. We are waiting for the html page to load, then we press the page reload button and observe how the page will change.

*Screenshots:*

<a href="https://ibb.co/VW3htN3"><img src="https://i.ibb.co/gM6X376/IMG-20220407-144917-325.jpg" alt="IMG-20220407-144917-325" border="0"></a>

<a href="https://ibb.co/z6hKMS2"><img src="https://i.ibb.co/9Z9RDq4/IMG-20220407-144914-023.jpg" alt="IMG-20220407-144914-023" border="0"></a>
