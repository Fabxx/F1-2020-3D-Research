# Ferrari Indexes

deleting 00000010 bytes to 00 removes entirely the cell mesh, so it's not there

00000020 removes the nose ahead only

00000030 removes the back of the cell where the gopro is

00000040-000000A0 removes more the back

000000B0-E0 nothing noticable, E0 Crashes if edited partially to bytes of 00

000000F0 Nothing noticable

00000100-110 Nothing Noticable, by removing from 020 to 110 does not affect the halo

00000120 byte 06 and 00000130-1F0 is under safety cell

00000200-240 nothing

from 00000300-3E0 is the rear wing bumper

Currently the halo was removed only by removing the bytes from 020 to 120, but it doesn't remove only the halo, but also some other car parts, if there are linked bytes between the memory regions to remove the halo, it will be much harder to discover it

I think that now i have to try to edit each string individually without editing the others, and see how they affect the model from 020 to 110

editing 00000150 affects the halo color, becoming the same color as the car
