# CompArchLab3

For this lab my task was to create the decoder for our reg-file. After starting by labeling our
select lines as well as our outputs, each was given the appropriate size bus.

for my implementation, I opted to use pure combinational logic opposed to behavioral. This meant
that I did not have to use a case statement. 

One by one, all outputs were assigned to be the combinational logic of the inputs. For example,
to assign the value of dout[0], all the select lines had to be off. Additionally, all 4 of the select
lines were & together.
