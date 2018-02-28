# multi-label-dataset

#all datasets contain "data" and "target";

#format:

#data: data_num*features_size; target: num_class*data_num

#positive_class: 1; negative_class: -1

#specific-features-dataset

#the data is processed by LIFT algorithm and generates new specific feature;

#sf_num: [n1,n2,n3,...,nq]

#It means that this dataset contains q labels,the i_th label's specific features is ni dimensions;the specific features are in order.