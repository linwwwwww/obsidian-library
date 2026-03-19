For strong spectral line sources (like RFI sources), the Gibbs phenomenon may cause ringing across the frequency channels of an observation. This is called the Gibbs pheomenon and a proven remedy is the Hanning smoothing algorithm. Hanning smoothing is a running mean across the spectral axis with a triangle as a smoothing kernel. The central channel is weighted by 0.5 and the two adjacent channels by 0.25 to preserve the flux. Hanning smoothing significantly reduces Gibbs ringing but there’s no gain without a penalty and here it is the loss of a factor of two in spectral resolution.


linear parameters in Barolo：
